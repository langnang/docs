# Node

## Install

### Install for Docker

**拉取镜像**

```sh
# 最新版本
docker pull node:latest
# 指定版本
docker pull node:20

docker pull node:alpine

docker pull node:slim

docker pull node:lts-alpine

docker pull node:lts-slim
```

**查看本地镜像**

```sh
docker images --filter "reference=node:*"
docker images --filter "reference=*/node:*"

# REPOSITORY  TAG          IMAGE ID       CREATED       SIZE
# node        alpine       77f3c4d1f33c   2 days ago    237MB
# node        slim         0cce74a5708f   2 days ago    334MB
# node        latest       a2ed436bacdc   2 days ago    1.63GB
# node        lts-alpine   cb3143549582   3 days ago    229MB
# node        lts-slim     c407baf6e71f   3 days ago    326MB
# node        20           abcf9c98af22   3 weeks ago   1.58GB
```

**运行容器**

```sh
docker run -itd --name node-server node
```

**安装成功**

```sh
docker exec -it node-server /bin/bash
```

### Install for Docker Compose

@[code](./compose.yaml)
