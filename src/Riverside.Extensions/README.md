# `Riverside.Extensions`

#### Helpful tools and classes for building modern apps.

---

`Riverside.Extensions` is a handy library containing small helpers and utilities, particularly algorithms, that are united in a stable and agnostic manner.
It targets .NET Standard 2.0, .NET 8 and .NET Framework 4.6.2 - exactly the same as the `Microsoft.Extensions` assembly.

The most prominent class in `Riverside.Extensions` is `Riverside.Extensions.Http`, which contains various HTTP interaction functions that use the algorithms exposed by `Riverside.Extensions` and serves as an example for how this library could be used.
Other various classes include rate limiters, retry policies, circuit breakers, and task schedulers.
