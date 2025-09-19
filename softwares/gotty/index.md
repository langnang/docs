# Gotty

## Install

### Install to Docker

```shell

```

```yml
services:
  gotty:
    image: yudai/gotty
    container_name: gotty
    ports:
      - 0:8080
    restart: unless-stopped
    network_mode: bridge
```
