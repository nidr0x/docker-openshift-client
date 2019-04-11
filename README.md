# OpenShift client for Docker #

![Docker Build Status](https://img.shields.io/docker/build/nidr0x/openshift-client.svg) ![Docker Pulls](https://img.shields.io/docker/pulls/nidr0x/openshift-client.svg) ![Docker Stars](https://img.shields.io/docker/stars/nidr0x/openshift-client.svg)

Docker container with OpenShift client.

## Features ##
- Built on Minideb latest release
- Possibility to choose the OC client version via environment variables
- Ideal for CI/CD purposes

## Usage ##
**Example:** 

Build:

`$ docker build -t openshift-client .`

Running client:

`$ docker run --rm -it openshift-client oc version`
