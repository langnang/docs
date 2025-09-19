# Nginx

## Install

### Install to Docker

```shell

```

```yml
services:
  nginx:
    image: nginx:latest
    container_name: nginx
    ports:
      - 0:80
    volumns:
      - /etc/nginx
      - /usr/share/nginx/html
      - /var/log/nginx
    restart: always
    network_mode: bridge
```
