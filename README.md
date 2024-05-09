Docker Oracle Linux Systemd
===========================

This Dockerfile can build containers capable to use systemd.

[![build status badge](https://img.shields.io/github/actions/workflow/status/zasfe/docker-oraclelinux-systemd/build-push-action.yml?branch=main&label=GitHub%20CI)](https://github.com/zasfe/docker-oraclelinux-systemd/actions?query=workflow%3A%22GitHub+CI%22+branch%3Amain) 
![Docker Automated build](https://img.shields.io/docker/automated/zasfe/oraclelinux?label=Docker%20Automated%20build)
![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/zasfe/oraclelinux?label=Docker%20Cloud%20Automated%20build)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/zasfe/oraclelinux?label=Docker%20Cloud%20Build%20Status)

[![Docker Image Version (tag)](https://img.shields.io/docker/v/zasfe/oraclelinux/main)](https://hub.docker.com/r/zasfe/oraclelinux)
[![Docker Stars](https://img.shields.io/docker/stars/zasfe/oraclelinux.svg)](https://hub.docker.com/r/zasfe/oraclelinux) 
[![Docker Pulls](https://img.shields.io/docker/pulls/zasfe/oraclelinux.svg)](https://hub.docker.com/r/zasfe/oraclelinux) 
[![Docker Image Size (tag)](https://img.shields.io/docker/image-size/zasfe/oraclelinux/main?label=Docker%20Image%20Size)](https://hub.docker.com/r/zasfe/oraclelinux) 

[![oraclelinux build status](https://img.shields.io/docker/cloud/build/robertdebock/oraclelinux.svg)](https://hub.docker.com/repository/docker/robertdebock/oraclelinux)

Branches
--------

This repository has multiple branches that relate to Oracle Linux versions.

|Branch |Oracle Linux Version|Docker image tag|
|-------|--------------|----------------|
|master |latest (8)    |latest          |
|7      |7             |7               |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  robertdebock/oraclelinux
```
