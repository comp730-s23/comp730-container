# COMP 730 Docker Image

This docker image defines the environment for COMP 730.

## Building from scratch

`docker build .`

For more detailed output, use:

`docker build . --progress=plain`

## Push to dockerhub

Dockerhub is configured to automatically build and update the
`comp730:latest` tag upon a push to the master branch.
