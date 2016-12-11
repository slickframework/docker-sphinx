# Sphinx Docker image

#### Python documentation generator

Sphinx is a tool that makes it easy to create intelligent and beautiful documentation,
written by [Georg Brandl](https://github.com/birkenfeld) and licensed under the BSD license.

This image was created to facilitate the usage and configuration for your project documentation.

## Usage

``` bash
docker run --rm -it --name sphinx -v $PWD/docs:/docs slickframework/sphinx 
```