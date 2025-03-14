# Hello World

Practice integrating Flask, Docker, GitHub (Actions) and AWS (ECR and ECS)

## Pre-requisites

- Python >= 3.10
- Docker

## Build

```bash
docker build --tag hello-docker .
```

## Run Local

```bash
docker run -d -p 5001:5000 hello-docker
```

## References

1. [How to Dockerize a Flask Application](https://www.freecodecamp.org/news/how-to-dockerize-a-flask-app/)
