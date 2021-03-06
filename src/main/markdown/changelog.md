# Lagom Change Log

## Lagom 1.0.0-M2

*Released 5 May 2016*

Second MVP release.  The major change in this release is that `ServiceCall` no longer has an ID parameter, instead parameters extracted from the URL are passed directly to the service interface method.  See issue [99](https://github.com/lagom/lagom/pull/99) for more details, and the [Service Descriptors](/documentation/1.0.x/ServiceDescriptors.html) documentation.

* [26](https://github.com/lagom/lagom/issues/26) Fix Cassandra chewing 100% of CPU
* [32](https://github.com/lagom/lagom/issues/32) Ensure default memory options are suitable for Lagom
* [41](https://github.com/lagom/lagom/issues/41) Improve service locator port conflict error reporting
* [53](https://github.com/lagom/lagom/pull/53) Improve dev mode specific dependency injection
* [75](https://github.com/lagom/lagom/pull/75) Ensure query parameters get added to client requests
* [91](https://github.com/lagom/lagom/issues/91) Fix Cassandra reconnection issues
* [99](https://github.com/lagom/lagom/pull/99) Rework URL parameter handling
* [102](https://github.com/lagom/lagom/pull/102) Ensure service interfaces can be implemented using a Scala trait

## Lagom 1.0.0-M1

*Released 10 March 2016*

First MVP release.