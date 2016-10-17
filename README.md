# docker-yarn

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to use the yarn package manager. Currently being used with [wercker](https://app.wercker.com), but should meet the requirements for most CI systems.

## Details

### Base Image

* [node (boron)](https://hub.docker.com/r/library/node/) - The latest Node LTS (Boron) image

### Additional Node Modules

* [yarn](https://yarnpkg.com) - The yarn package manager. Installed globally (via `npm install -g yarn`).
