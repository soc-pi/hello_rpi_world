# rpi crossc ompile with docker

## Description

This project demonstrates cross-compiling an application using Docker for the Raspberry Pi family of boards.

## Prerequisites

- Docker installed on your system
- Make installed on your system

## Build

To build the project using Docker, run the following command:

```sh
make build
```

## Run

To run the built binary, execute the following command:

```sh
make run
```

## Test

To run the tests, execute the following command:

```sh
make test
```

## Lint

To run cpplint, execute the following command:

```sh
make lint
```

## Format

To format the code using clang-format, execute the following command:

```sh
make format
```

## Clean

To clean the build directory, execute the following command:

```sh
make clean
```

## Rebuild

To clean and build the project, execute the following command:

```sh
make rebuild
```

## Docker Shell

To open a shell inside the Docker container, execute the following command:

```sh
make docker-shell
```

## Docker Clean

To clean the Docker environment, execute the following command:

```sh
make docker-clean
```

## Docker Test

To run tests inside the Docker container, execute the following command:

```sh
make docker-test
```

## Help

To display the available Makefile targets, execute the following command:

```sh
make help
```
