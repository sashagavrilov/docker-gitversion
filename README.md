# Supported tags and `Dockerfile` links
- [`3.3.6`, `3.3`, `stable` (*3.3.6/Dockerfile*)](https://github.com/ilucker/docker-gitversion/blob/master/3.3.6/Dockerfile)
- [`4.0.0-beta.7`, `4.0.0`, `4.0`, `latest` (*4.0.0/Dockerfile*)](https://github.com/ilucker/docker-gitversion/blob/master/4.0.0/Dockerfile)

# What is GitVersion

GitVersion is a tool to help you achieve *Semantic Versioning* on your project.

* [GitVersion Project homepage](https://github.com/GitTools/GitVersion)

# How to use this image

This image will run GitVersion Command Line tool. It expects the git rempository to be bound at /src

    $ docker run --rm -v "$PWD:/src" ilucker/gitversion /h