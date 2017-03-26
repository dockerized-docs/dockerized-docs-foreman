# dockerized-docs-foreman

# What is it? #
Dockerzied theforeman.org site + foreman documentation for offline use.

# Image description #
- Base image: `ruby:latest`
- The most current theforeman.org `gh-pages` branch is cloned
- Jekyll is installed using bundle

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-foreman

```

You can test it by visiting http://container-ip:8080
