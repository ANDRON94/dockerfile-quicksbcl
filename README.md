# Quicksbcl Dockerfile

This repository contains **Dockerfile** of [Quicklisp](https://www.quicklisp.org/beta/) for Docker's automated
build published to the [Docker Hub](https://hub.docker.com/r/andron94/dockerfile-quicksbcl/).

## Base Docker Image

+ [andron94/dockerfile-sbcl:2.1.1](https://hub.docker.com/r/andron94/dockerfile-sbcl/)

## Installation

1.  Install [Docker](https://docs.docker.com/engine/installation/).
2.  Download automated build from public Docker Hub Registry:
    ```sh
    docker pull andron94/dockerfile-quicksbcl:[TAG]
    ```

## Usage

### Run `SBCL` session

```sh
docker run --rm -it andron94/dockerfile-quicksbcl:[TAG]
```

### Run `shell` session

```sh
docker run --rm -it --entrypoint /bin/sh andron94/dockerfile-quicksbcl:[TAG]
```
