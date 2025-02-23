# Java JUnit5

A minimal setup with Java, [JUnit5](https://junit.org/junit5/), [AssertJ](https://assertj.github.io/doc/) and [Mockito](https://site.mockito.org/) to get you started.

You can use [gradle](https://gradle.org/) or [maven](https://maven.apache.org/)

[More complicated JUnit5 setups](https://github.com/junit-team/junit5-samples)

## Setup

    git clone https://github.com/swkBerlin/kata-bootstraps
    cd java/junit5

Open as preexisting project in your favorite IDE and choose between gradle or maven nature

## (optional) IDE Setup

Run `./gradlew idea` to build [idea](https://www.jetbrains.com/idea) project.

## Running Tests

To execute the tests either run `./gradlew test`, `mvn test` or run the tests from the IDE you are using

## Running with docker compose

With this method you don't have to install java on your computer.
The tests will be run inside a docker container.
It may be slower to run than having a real Jdk installed on your machine.

Prerequisites : install a recent version on docker.
At first, the docker image and the maven dependencies wil download.
Then, when running again, it will be fast to run.

```shell
# Run with java 8
docker compose run java8
# Run with java 11
docker compose run java11
# Run with java 17
docker compose run java17
# Run with java 18
docker compose run java18
# Run with gradle latest
docker compose run gradle
```

## Test Libraries Available from the Get-Go
- [JUnit 5.8.2](https://junit.org/junit5/docs/snapshot/release-notes/#release-notes-5.8.2)
- [AssertJ 3.22.0](https://assertj.github.io/doc/#assertj-core-release-notes)
- [Mockito 4.3.1](https://github.com/mockito/mockito/releases)


## Additional Libraries
- [Vavr](https://www.vavr.io/) a functional library for Java.


This repo was tested with [idea](https://www.jetbrains.com/idea) [2020.3.1](https://confluence.jetbrains.com/display/IDEADEV/IntelliJ+IDEA+2020.3.1+%28203.6682.168+build%29+Release+Notes), if you encounter problems please open an issue or send a pull request.

Have fun!
