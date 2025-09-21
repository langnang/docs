# Software

## Install

### Install for Docker

```shell

```

```yml
services:
  mediawiki:
  image: mediawiki:latest
  restart: always
  ports:
    - "0:80"
  volumes:
    - ./images:/var/www/html/images
```
