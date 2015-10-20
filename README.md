Apache Spark on Docker with Anaconda Python
==========

This repository contains a Docker file to build a Docker image with Apache Spark with Anaconda Python. This Docker image depends on [Spark Docker](https://github.com/sequenceiq/docker-spark) image.

##Pull the image from Docker Repository
```
docker pull logbase/spark-anaconda
```

## Building the image
```
docker build --rm -t logbase/spark-anaconda .
```

## Running the image
```
docker run -it -p 4040:4040 -p 8888:8888 logbase/spark-anaconda
```