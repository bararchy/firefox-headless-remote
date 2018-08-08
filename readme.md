[![version](https://img.shields.io/badge/firefox-61-green.svg?style=flat-square)](https://packages.ubuntu.com/bionic/firefox) [![build](https://img.shields.io/docker/build/deepsweet/firefox-headless-remote.svg?label=build&style=flat-square)](https://hub.docker.com/r/deepsweet/firefox-headless-remote/) [![size](https://img.shields.io/microbadger/image-size/deepsweet/firefox-headless-remote.svg?label=size&style=flat-square)](https://microbadger.com/images/deepsweet/firefox-headless-remote)

Dockerized Firefox in headless [Marionette](https://vakila.github.io/blog/marionette-act-i-automation/) mode.

```sh
docker run -it --rm --shm-size 2g -p 2828:2828 deepsweet/firefox-headless-remote:61
```
