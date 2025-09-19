# Software

## Install

### Install to Docker

```shell

```

```yml
services:
  speedtest-x:
    container_name: speedtest-x
    ports:
      - 0:80
    image: badapple9/speedtest-x
    restart: unless-stopped
    network_mode: bridge
```
