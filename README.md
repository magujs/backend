# Backend Repository

[![Build Status](https://travis-ci.org/Studio-Link-v2/backend.svg?branch=master)](https://travis-ci.org/Studio-Link-v2/backend)

This repository contains the studio link - baresip modules and build environment

## Build Requirements

- OpenSSL
- LV2 (optional)
- Header files for OpenSSL, ALSA and JACK

## Build on Linux

```export TRAVIS_OS_NAME="linux"; build/build.sh```

### Build on Ubuntu 16.04

The needed header files are in these packages:  
libssl-dev libasound2-dev libjack-jackd2-dev

## Build on OSX

```export TRAVIS_OS_NAME="osx"; build/build.sh```

## Build for Windows on Archlinux

```export BUILD_OS="windows64"; build/build_windows.sh```
