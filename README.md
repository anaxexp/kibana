# Kibana Docker Container Image

[![Build Status](https://travis-ci.org/anaxexp/kibana.svg?branch=master)](https://travis-ci.org/anaxexp/kibana)
[![Docker Pulls](https://img.shields.io/docker/pulls/anaxexperience/kibana.svg)](https://hub.docker.com/r/anaxexperience/kibana)
[![Docker Stars](https://img.shields.io/docker/stars/anaxexperience/kibana.svg)](https://hub.docker.com/r/anaxexperience/kibana)
[![Docker Layers](https://images.microbadger.com/badges/image/anaxexperience/kibana.svg)](https://microbadger.com/images/anaxexperience/kibana)


## Docker Images

* All images are based on Alpine Linux
* Base image: [anaxexperience/alpine](https://github.com/anaxexp/alpine)
* [TravisCI builds](https://travis-ci.org/anaxexp/kibana) 
* [Docker Hub](https://hub.docker.com/r/anaxexp/kibana)

Supported tags and respective `Dockerfile` links:

* `6`, `6.2`, `latest` [_(Dockerfile)_](https://github.com/anaxexp/kibana/tree/master/Dockerfile)
* `6.1` [_(Dockerfile)_](https://github.com/anaxexp/kibana/tree/master/Dockerfile)
* `6.0` [_(Dockerfile)_](https://github.com/anaxexp/kibana/tree/master/Dockerfile)
* `5`, `5.6` [_(Dockerfile)_](https://github.com/anaxexp/kibana/tree/master/Dockerfile)
* `5.5` [_(Dockerfile)_](https://github.com/anaxexp/kibana/tree/master/Dockerfile)
* `5.4` [_(Dockerfile)_](https://github.com/anaxexp/kibana/tree/master/Dockerfile)

For better reliability we additionally release images with stability tags (`anaxexperience/kibana:6-X.X.X`) which correspond to [git tags](https://github.com/anaxexp/kibana/releases). We **strongly recommend** using images only with stability tags. 

## Orchestration Actions

Usage:
```
make COMMAND [params ...]
 
commands:
    check-ready [host max_try wait_seconds delay_seconds]
 
default params values:
    host localhost
    max_try 1
    wait_seconds 1
    delay_seconds 0
```

## Deployment

Deploy Kibana with Elasticsearch to your own server via [![AnaxExp](https://www.google.com/s2/favicons?domain=anaxexp.io) Anaxexp](https://anaxexp.io).
