# ZIO MicroService Example

This is an example showing how to create a microservice using ZIO with Scala. This is a very basic example of a microservice which communicate through HTTP Endpoints, store data in Postgres using Doobie, manage configuration using ZIO Config and HOCON, log and tracing using ZIO-Logging and managing metrics using ZIO-Metrics. For HTTP endpoints I have used ZIO HTTP which is easy to use and as mentioned in their benchmarks is quite performant.

---
## Todo

|TODO | Library | Status |
|-----|---------|--------|
|HTTP Endpoint | ZIO-HTTP | Done ✅|
|DB Library| Doobie | Done ✅|
|Configuration | ZIO-Config | Done ✅|
|Logging  | ZIO-Logging | Done ✅|
|Metric  | ZIO-Metrics | In Progress 🔛|
|Unit Testing| ZIO-Test| In Progress 🔛|

## References

1.  [ZIO App Architecture by Kit Langton](https://www.youtube.com/watch?v=yXcqjQ7Kcwk)
2. [Production-grade Microservices with ZIO by Itamar Ravid](https://www.youtube.com/watch?v=oMJ1RMdR7wg)