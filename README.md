[![Docker Build Status](https://img.shields.io/docker/build/zenika/kotlin.svg)](https://hub.docker.com/r/zenika/kotlin/) [![Docker Pulls](https://img.shields.io/docker/pulls/zenika/kotlin.svg)](https://hub.docker.com/r/zenika/kotlin/)

### Supported tags and respective `Dockerfile` links

#### 1.3

 * `1.3-jdk11` [(1.3/jdk11/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk11/Dockerfile)

 * `1.3-jdk11-slim` [(1.3/jdk11/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk11/slim/Dockerfile)

 * `1.3-jdk10` [(1.3/jdk10/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk10/Dockerfile)

 * `1.3-jdk10-slim` [(1.3/jdk10/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk10/slim/Dockerfile)

 * `1.3-jdk8` [(1.3/jdk8/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk8/Dockerfile)

 * `1.3-jdk8-alpine` [(1.3/jdk8/alpine/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk8/alpine/Dockerfile)

 * `1.3-jdk8-slim` [(1.3/jdk8/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.3/jdk8/slim/Dockerfile)

#### 1.2

 * `1.2-jdk11` [(1.2/jdk11/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk11/Dockerfile)

 * `1.2-jdk11-slim` [(1.2/jdk11/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk11/slim/Dockerfile)

 * `1.2-jdk10` [(1.2/jdk10/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk10/Dockerfile)

 * `1.2-jdk10-slim` [(1.2/jdk10/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk10/slim/Dockerfile)

 * `1.2-jdk8` [(1.2/jdk8/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk8/Dockerfile)

 * `1.2-jdk8-alpine` [(1.2/jdk8/alpine/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk8/alpine/Dockerfile)

 * `1.2-jdk8-slim` [(1.2/jdk8/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2/jdk8/slim/Dockerfile)

#### 1.2-eap

 * `1.2-eap-jdk11` [(1.2-eap/jdk11/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk11/Dockerfile)

 * `1.2-eap-jdk11-slim` [(1.2-eap/jdk11/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk11/slim/Dockerfile)

 * `1.2-eap-jdk10` [(1.2-eap/jdk10/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk10/Dockerfile)

 * `1.2-eap-jdk10-slim` [(1.2-eap/jdk10/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk10/slim/Dockerfile)

 * `1.2-eap-jdk8` [(1.2-eap/jdk8/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk8/Dockerfile)

 * `1.2-eap-jdk8-alpine` [(1.2-eap/jdk8/alpine/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk8/alpine/Dockerfile)

 * `1.2-eap-jdk8-slim` [(1.2-eap/jdk8/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.2-eap/jdk8/slim/Dockerfile)

#### 1.1

 * `1.1-jdk11` [(1.1/jdk11/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk11/Dockerfile)

 * `1.1-jdk11-slim` [(1.1/jdk11/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk11/slim/Dockerfile)

 * `1.1-jdk10` [(1.1/jdk10/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk10/Dockerfile)

 * `1.1-jdk10-slim` [(1.1/jdk10/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk10/slim/Dockerfile)

 * `1.1-jdk8` [(1.1/jdk8/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk8/Dockerfile)

 * `1.1-jdk8-alpine` [(1.1/jdk8/alpine/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk8/alpine/Dockerfile)

 * `1.1-jdk8-slim` [(1.1/jdk8/slim/Dockerfile)](https://github.com/Zenika/docker-kotlin/blob/master/1.1/jdk8/slim/Dockerfile)

### What is Kotlin

Kotlin is a statically-typed programming language that runs on the Java virtual machine and also can be compiled to JavaScript source code or use the LLVM compiler infrastructure. Its primary development is from a team of JetBrains programmers based in Saint Petersburg, Russia. While the syntax is not compatible with Java, Kotlin is designed to interoperate with Java code and is reliant on Java code from the existing Java Class Library, such as the collections framework.

See https://en.wikipedia.org/wiki/Kotlin_%28programming_language%29 for more information.

![Kotlin Logo](https://github.com/Zenika/docker-kotlin/raw/master/Kotlin-logo.png)

### Usage

Start using the Kotlin REPL : `docker container run -it --rm zenika/kotlin`

See Kotlin compiler version : `docker container run -it --rm zenika/kotlin kotlinc -version`

See Kotlin compiler help : `docker container run -it --rm zenika/kotlin kotlinc -help`

### Reference

 * Kotlin website : https://kotlinlang.org

 * Where to file issues : https://github.com/Zenika/docker-kotlin/issues

 * Maintained by : https://www.zenika.com
