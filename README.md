# GraalVM demo

## Setup

* install GraalVM JDK (recommended via [sdkman](https://sdkman.io/))
* install `native-image` via `gu`

## Build native image

```shell
mvn -Pnative clean package
```

The build may take several minutes, depending on your hardware (on my i7 it takes about 2 minutes).

## Start native image

```shell
./target/graalvm
```
