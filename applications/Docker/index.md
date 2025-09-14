# Docker

## 安装

### Install for Windows

```batch
# 迁移安装文件
move "C:\Program Files\Docker\*.*" "D:\Programs\Docker\"

# 创建符号链接
mklink /j "C:\Program Files\Docker" "D:\Programs\Docker"
```

1. 手动创建必要目录

在 D 盘创建以下目录：

```txt
C:\Program Files\Docker
C:\Users\%USERNAME%\AppData\Local\Docker
D:\Programs\Docker
D:\Programs\Docker\Data
确保目录名称与上述一致，否则可能导致安装失败。
```

2. 使用管理员权限安装

下载 Docker Desktop 安装程序后，打开命令提示符（以管理员身份运行），进入安装程序所在目录。例如：

运行以下命令进行安装：

```batch
cd D:\Downloads

curl -L "https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe" -o "Docker Desktop Installer.exe"

@rem start /w "" "Docker Desktop Installer.exe" install -accept-license --installation-dir="D:\Programs\Docker" --wsl-default-data-root="D:\Programs\Docker\data" --windows-containers-default-data-root="D:\\Programs\\Docker"

start /w "" "Docker Desktop Installer.exe" install

docker version

docker run hello-world

@rem C:\Program Files\Docker
xcopy "C:\Program Files\Docker" "D:\Programs\Docker" /H /E /Y
rd "C:\Program Files\Docker" /S /Q
mklink /j "C:\Program Files\Docker" "D:\Programs\Docker"

@rem C:\Users\%USERNAME%\.docker
xcopy "C:\Users\%USERNAME%\.docker" "D:\Programs\Docker\.docker" /H /E /Y
rd "C:\Users\%USERNAME%\.docker" /S /Q
mklink /j "C:\Users\%USERNAME%\.docker" "D:\Programs\Docker\.docker"

@rem C:\Users\%USERNAME%\AppData\Local\Docker
xcopy "C:\Users\%USERNAME%\AppData\Local\Docker" "D:\Programs\Docker\AppData" /H /E /Y
rd "C:\Users\%USERNAME%\AppData\Local\Docker" /S /Q
mklink /j "C:\Users\%USERNAME%\AppData\Local\Docker" "D:\Programs\Docker\AppData"
```

3. 更新环境变量

如果安装完成后仍然报错，可能是环境变量未正确更新。使用 PowerShell 更新：

```ps1
$oldPath = [System.Environment]::GetEnvironmentVariable("Path", [System.EnvironmentVariableTarget]::Machine)
$newPath = $oldPath + ";D:\Programs\Docker\resources\bin"
[System.Environment]::SetEnvironmentVariable("Path", $newPath, [System.EnvironmentVariableTarget]::Machine)
```

完成后重启电脑。

4. 测试安装是否成功

在命令提示符中运行以下命令：

docker version
如果输出 Docker 版本信息，则说明安装成功。

5. 运行测试容器

验证 Docker 是否正常工作：

docker run hello-world

### 中文化

```batch

```

## 关闭 Docker

```sh
# 禁用 docker 开机自启
systemctl disable docker
# 关停 docker 服务
systemctl stop docker
```

### Docker 网络模式：

Bridge 模式：默认的网络模式，容器通过虚拟网络桥进行通信。
Host 模式：容器与宿主机共享网络命名空间。
None 模式：禁用所有网络功能。
Overlay 模式：用于跨多个 Docker 主机的容器通信。
Macvlan 模式：每个容器拥有独立的 MAC 地址和 IP 地址。

### 端口映射：

通过将宿主机的端口映射到容器内的端口，实现外部网络对容器内服务的访问。

### 容器互联：

通过容器名称建立网络通信隧道，使容器之间可以相互通信。

## 议题

- `This can prevent Docker from starting. Use at your own risk.`
- `connect ENOENT \\.\pipe\dockerBackendApiServer`
- `Docker Engine Stopped`
- `Extensions Failed to fetch extensions.`
- `An unexpected error occurred. Restart Docker Desktop.`
- `Docker Desktop distro installation failed`
- `WARNING: daemon is not using the default seccomp pro`
- `Error response from daemon: Get "https://registry-1.docker.io/v2/": net/http: request canceled while waiting for connection (Client.Timeout exceeded while awaiting headers)`
