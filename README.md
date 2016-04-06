# container-siege
siege stress testing tool based on ubuntu:14.04

### Building
```
docker build -t siege .
```

### Usage
To show valid parameters/help:
```
docker run --rm siege
```
To run siege for a specific site:
```
docker run --rm siege [attibutes] [site]
```
