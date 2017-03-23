# GDAL 2.1.1 Docker Image

This is an Ubuntu 14.04 (Trusty) derived image containing the Geospatial Data Abstraction Library (GDAL) 2.1.1 compiled with python, hdf5 and geos drivers.

## Build the image on your own
```bash
$ git clone https://github.com/fgriberi/gdal-trusty.git
$ cd gdal-trusty
$ docker build -t gdal-trusty .
```

## Use image from DockerHub
```bash
docker pull friberi/gdal-trusty
```
