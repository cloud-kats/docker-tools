# docker-tools

## Create Locally
```
$ cd <Folder>

$ ARG DOCKER_REGISTRY
$ ARG ARCH
$ ARG OS
$ ARG OS_RELEASE
$ ARG TIMESTAMP

$ FROM ${DOCKER_REGISTRY:-none}/{ARCH:-amd64}/{OS:-ubuntu}/${RELEASE:-bionic}:${TIMESTAMP:-latest}
```
