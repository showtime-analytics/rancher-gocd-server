docker-gocd-server
==================

A image to run GoCD server. It's based in "rawmind/rancher-jvm8".

## Build

```
docker build -t showtimeanalytics/rancher-gocd-server:<version> .
```

## Versions

- `16.5.0` [(Dockerfile)](https://github.com/showtimeanalytics/docker-gocd-server/blob/master/Dockerfile)

## Usage

You could configure Nexus mem params in execution time, setting that variables:
- SERVER_MEM="1024"
- SERVER_MAX_MEM="2048"

## Storage

If you want to assure data persistence, you need a persistent volume on /opt/go-server/work
