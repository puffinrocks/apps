# Puffin Apps

## Introduction

This is the application catalog for [Puffin](http://puffin.rocks).

## Adding a new application

All you need is a standard docker-compose.yml and README.md files - Puffin does not require any custom
application manifest.
Check how existing applications in this repository are configured as an example.

Once you have configured and tested the new application, please contact us to create a repository for it under
[puffinrocks](https://github.com/puffinrocks) organisation or
directly fork [apps](https://github.com/puffinrocks/apps) repository,
add your own repository to it as a submodule and submit a Pull Request with your changes.

If you run into any trouble, or would like to add an application to the wishlist,
please visit open an [issue on GitHub](https://github.com/puffinrocks/apps/issues) under this repository.

There is no strict policy which applications will be accepted to the Puffin catalog,
but the main conditions are free / open source license and relatively low memory footprint.

## Using applications without Puffin

Applications can be run independently of Puffin. To do that:
- set VIRTUAL_HOST environment variable before starting an app
- set-up puffin_front and puffin_back networks
- start _mail and _proxy container
