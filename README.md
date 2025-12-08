# Prashant Nagoorkar

Doing my bit improve modularity in software systems.<br/><br/>
[View my blog](https://baubit.net/blog)

---

## Baubit

A modular ecosystem for .NET applications. Configuration-driven composition, result pattern error handling, and high-performance primitives.

### Core

| Package | Description |
|---------|-------------|
| [![NuGet](https://img.shields.io/nuget/v/Baubit.DI.svg)](https://www.nuget.org/packages/Baubit.DI/)<br/>[**Baubit.DI**](https://github.com/pnagoorkar/Baubit.DI) | Modularity framework with configuration-driven module composition |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Configuration.svg)](https://www.nuget.org/packages/Baubit.Configuration/)<br/>[**Baubit.Configuration**](https://github.com/pnagoorkar/Baubit.Configuration) | Type-safe configuration builder with Result pattern and environment variable expansion |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.DI.Autofac.svg)](https://www.nuget.org/packages/Baubit.DI.Autofac/)<br/>[**Baubit.DI.Autofac**](https://github.com/pnagoorkar/Baubit.DI.Autofac) | Autofac support for Baubit.DI |

### High Performance

| Package | Description |
|---------|-------------|
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Identity.svg)](https://www.nuget.org/packages/Baubit.Identity/)<br/>[**Baubit.Identity**](https://github.com/pnagoorkar/Baubit.Identity) | Monotonic GuidV7 generator. Zero allocations, thread-safe, RFC 9562 compliant |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Caching.svg)](https://www.nuget.org/packages/Baubit.Caching/)<br/>[**Baubit.Caching**](https://github.com/pnagoorkar/Baubit.Caching) | Thread-safe ordered cache. O(1) lookups, two-tier storage, async enumeration |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Mediation.svg)](https://www.nuget.org/packages/Baubit.Mediation/)<br/>[**Baubit.Mediation**](https://github.com/pnagoorkar/Baubit.Mediation) | Mediator pattern with cache-backed routing. 3-4x [faster](https://github.com/pnagoorkar/Baubit.Mediation/blob/master/Baubit.Mediation.Benchmark/results.md) than [MediatR](https://github.com/LuckyPennySoftware/MediatR) |

### Utilities

| Package | Description |
|---------|-------------|
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Traceability.svg)](https://www.nuget.org/packages/Baubit.Traceability/)<br/>[**Baubit.Traceability**](https://github.com/pnagoorkar/Baubit.Traceability) | Error handling and result tracing using FluentResults |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Reflection.svg)](https://www.nuget.org/packages/Baubit.Reflection/)<br/>[**Baubit.Reflection**](https://github.com/pnagoorkar/Baubit.Reflection) | Enhanced reflection with Result pattern error handling |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Collections.svg)](https://www.nuget.org/packages/Baubit.Collections/)<br/>[**Baubit.Collections**](https://github.com/pnagoorkar/Baubit.Collections) | Thread-safe collection types (ConcurrentList<T>) |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Tasks.svg)](https://www.nuget.org/packages/Baubit.Tasks/)<br/>[**Baubit.Tasks**](https://github.com/pnagoorkar/Baubit.Tasks) | Task utilities with FluentResults integration |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Networking.svg)](https://www.nuget.org/packages/Baubit.Networking/)<br/>[**Baubit.Networking**](https://github.com/pnagoorkar/Baubit.Networking) | TCP utilities for testing and inter-process communication |

### Persistence

| Package | Description |
|---------|-------------|
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Caching.LiteDB.svg)](https://www.nuget.org/packages/Baubit.Caching.LiteDB/)<br/>[**Baubit.Caching.LiteDB**](https://github.com/pnagoorkar/Baubit.Caching.LiteDB) | LiteDB-backed L2 store implementation for [**Baubit.Caching**](https://github.com/pnagoorkar/Baubit.Caching).<br/>Useful for session persistance, rewind-replay. |

### DI Extensions

| Package | Description |
|---------|-------------|
| [![NuGet](https://img.shields.io/nuget/v/Baubit.DI.Extensions.svg)](https://www.nuget.org/packages/Baubit.DI.Extensions/)<br/>[**Baubit.DI.Extensions**](https://github.com/pnagoorkar/Baubit.DI.Extensions) | Extensions for adding modules directly to IServiceCollection |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Caching.DI.svg)](https://www.nuget.org/packages/Baubit.Caching.DI/)<br/>[**Baubit.Caching.DI**](https://github.com/pnagoorkar/Baubit.Caching.DI) | DI modules for Baubit.Caching |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Caching.LiteDB.DI.svg)](https://www.nuget.org/packages/Baubit.Caching.LiteDB.DI/)<br/>[**Baubit.Caching.LiteDB.DI**](https://github.com/pnagoorkar/Baubit.Caching.LiteDB.DI) | DI modules for Baubit.Caching.LiteDB |
| [![NuGet](https://img.shields.io/nuget/v/Baubit.Mediation.DI.svg)](https://www.nuget.org/packages/Baubit.Mediation.DI/)<br/>[**Baubit.Mediation.DI**](https://github.com/pnagoorkar/Baubit.Mediation.DI) | DI modules for Baubit.Mediation |

### Testing

| Package | Description |
|---------|-------------|
| [![NuGet](https://img.shields.io/nuget/v/Baubit.xUnit.svg)](https://www.nuget.org/packages/Baubit.xUnit/)<br/>[**Baubit.xUnit**](https://github.com/pnagoorkar/Baubit.xUnit) | xUnit integration with scenario-based testing |

---

## Other Projects

| Project | Description |
|---------|-------------|
| [![npm version](https://img.shields.io/npm/v/fluent-results.svg)](https://www.npmjs.com/package/fluent-results)<br/>[**fluent-results**](https://github.com/pnagoorkar/fluent-results) | Dependency-free success/failure pipelines for JavaScript & TypeScript |

---

## Open Source Contributions

- [**Autofac.Configuration**](https://github.com/autofac/Autofac.Configuration) — Module construction improvements
