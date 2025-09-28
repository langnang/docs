# Kettle

## Install

### Install for Docker

```shell

```

```yml
version: "3"
services:
  kettle:
    image: pentaho/kettle
    container_name: kettle
    ports:
      - "0:8080"
    volumes:
      - ./kettle:/data
    environment:
      - KETTLE_HOME=/data
```
