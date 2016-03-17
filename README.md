vamp-test
==============

vamp-test image based in alpine-nginx

To build

```
docker build -t <repo>/vamp-test:<version> .
```

To run:

```
docker run -it <repo>/vamp-test:<version> 
```

## Versions

- `0.0.1` [(Dockerfile)](https://github.com/rawmind0/vamp-test/blob/master/Dockerfile)

## Usage

This image compile and deploy to access vamp-test service. 

The nginx service is started with monit and check for the 80 port is listening.
