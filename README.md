# docker-grpc-python
Python docker images that installed grpc libraries.

[![CircleCI](https://circleci.com/gh/ushios/docker-grpc-python.svg?style=shield)](https://circleci.com/gh/ushios/docker-grpc-python)

## Usage

Using in from clause.
```Dockerfile
FROM ushios/grpc-python:3.6-alpine

RUN pip install -r requirements.txt
...
```

## Build all images

```console
$ docker-compose build
```