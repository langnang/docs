# Software

## Install

### Install for Docker

```shell

```

```yml
services:
  phpmyadmin:
    image: phpmyadmin:latest
    container_name: phpmyadmin
    ports:
      - 0:80
    deploy:
      resources:
        limits:
          memory: 500M
    restart: unless-stopped
    network_mode: bridge
```
