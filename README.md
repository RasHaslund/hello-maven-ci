# hello-maven-ci

[![Java CI with Maven](https://github.com/RasHaslund/hello-maven-ci/actions/workflows/ci.yml/badge.svg)](https://github.com/RasHaslund/hello-maven-ci/actions/workflows/ci.yml)

## Features

- Maven build with JUnit tests
- Automatic builds on every push
- Docker image automatically built and pushed to GitHub Container Registry

## Run Locally

```bash
docker run --rm ghcr.io/YOUR_USERNAME/hello-maven:latest
