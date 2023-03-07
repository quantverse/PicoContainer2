# Introduction

This is a patched version of (abandoned) PicoContainer v2 quickly hacked to
be usable on newer JDKs (tested with 11 and 17).

The version specifier is `2.15.1-SNAPSHOT`.

## Prerequisites

* JDK 11 or newer
* Apache Maven (tested with 3.9.0)

You will need to build a dev version of [paranamer](https://github.com/paul-hammant/paranamer)
and install the package locally (`v2.8.1-SNAPSHOT`) before building this package.

### Building This Package

```bash
mvn package -Dmaven.test.skip=true
```