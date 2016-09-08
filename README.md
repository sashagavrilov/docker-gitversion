# Supported tags and `Dockerfile` links
- [`latest` (*Dockerfile*)](https://github.com/ilucker/docker-gitversion/blob/master/3.3.6/Dockerfile)
- [`3.3.6` (*Dockerfile*)](https://github.com/ilucker/docker-gitversion/blob/master/3.3.6/Dockerfile)

# What is GitVersion

GitVersion is a tool to help you achieve *Semantic Versioning* on your project.

* [GitVersion Project homepage](https://github.com/GitTools/GitVersion)

# How to use this image

This image will run GitVersion Command Line tool. It expects the git rempository to be bound at /src

    $ docker run --rm -v "$PWD:/src" ilucker/gitversion /h