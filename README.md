# README #

This repository contains the KAS tool config files needed to build ELK Audio OS images.

### Install requirements ###
For a quick start you can use the [ELK Audio OS builder](https://github.com/elk-audio/elk-audio-os-builder) docker image
which comes with KAS tool and all the required packages installed.

Otherwise if you already have a machine set up for running bitbake you can install KAS on it.
Please read [KAS documentation](https://kas.readthedocs.io/en/latest/index.html) for the details.

### Building Elk Audio OS 1.1.0 Raspberry Pi 4 image ###
```bash
kas build raspberrypi4/raspberrypi4-elk-audio-os-v1.1.0.yml
```

Copyright 2017-2025 Elk Audio AB, Stockholm, Sweden.
