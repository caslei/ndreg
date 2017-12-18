# ndreg
Package that performs affine and LDDMM registration *easily* <br/>

## Sytem Requirements

The recommended way to use this package is to install [Docker](https://store.docker.com/search?offering=community&type=edition). Docker is currently available on OS X El Capitan 10.11 and newer macOS releases, the following Ubuntu versions: Zesty 17.04 (LTS), Yakkety 16.10, Xenial 16.04 (LTS), Trusty 14.04 (LTS), and Windows 10.

### Software Dependencies (with version numbers)

External libraries: <br/>
- Insight Segmentation and Registration Toolkit (ITK) -- 4.12.2

Python depedencies: <br/>
- jupyter -- (1.0.0)
- numpy -- (1.13.3)
- scikit-image -- (0.13.1)
- scikit-learn -- (0.19.1)
- scipy -- (1.0.0)
- SimpleITK -- (1.0.1)

### Versions tested on
We have tested the Docker image and build on macOS High Sierra (on MacBook Pro with 2.9 GHz Intel Core i7 and 16 GB RAM) and Ubuntu Xenial 16.04.3 LTS.

## Installation Guide

Once Docker is installed on your machine, pull the `neurodata/ndreg` image from Docker Hub [here](https://hub.docker.com/r/neurodata/ndreg) as follows: <br/>

`docker pull neurodata/ndreg` <br/>

It will typically take around 3 minutes to pull the entire image.

## Demo

### Instructions to run on data

In order to use the functionality built into this Docker image, you need to run the Docker image:

`docker run -p 8888:8888 neurodata/ndreg` <br/>

This should print a link to the terminal console that looks like this: <br/>

`http://0.0.0.0:8888/?token=SOME_TOKEN` <br/>

Go to this link in your browser by copying and pasting it. <br/>

### Expected Output

### Expected run time for demo

# Running



