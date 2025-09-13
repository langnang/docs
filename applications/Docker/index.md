# Docker

## 安装

```batch
# 迁移安装文件
move "C:\Program Files\Docker\*.*" "D:\Programs\Docker\"

# 创建符号链接
mklink /j "C:\Program Files\Docker" "D:\Programs\Docker"
```

### 安装到D盘

1. 手动创建必要目录

在D盘创建以下目录：

```txt
D:\Programs\Docker
D:\Programs\Docker\Data
确保目录名称与上述一致，否则可能导致安装失败。
```

2. 使用管理员权限安装

下载Docker Desktop安装程序后，打开命令提示符（以管理员身份运行），进入安装程序所在目录。例如：

cd D:\Downloads
运行以下命令进行安装：

```bat
start /w "" "Docker Desktop Installer.exe" install -accept-license --installation-dir="D:\Programs\Docker" --wsl-default-data-root="D:\Programs\Docker\data" --windows-containers-default-data-root="D:\\Programs\\Docker"
```

3. 更新环境变量

如果安装完成后仍然报错，可能是环境变量未正确更新。使用PowerShell更新：

```ps1
$oldPath = [System.Environment]::GetEnvironmentVariable("Path", [System.EnvironmentVariableTarget]::Machine)
$newPath = $oldPath + ";D:\Programs\Docker\resources\bin"
[System.Environment]::SetEnvironmentVariable("Path", $newPath, [System.EnvironmentVariableTarget]::Machine)
```

完成后重启电脑。

4. 测试安装是否成功

在命令提示符中运行以下命令：

docker version
如果输出Docker版本信息，则说明安装成功。

5. 运行测试容器

验证Docker是否正常工作：

docker run hello-world

## 议题

- `This can prevent Docker from starting. Use at your own risk.`
- `connect ENOENT \\.\pipe\dockerBackendApiServer`
- `Docker Engine Stopped`
- `Extensions Failed to fetch extensions.`
- `An unexpected error occurred. Restart Docker Desktop.`
- `Docker Desktop distro installation failed`
- `WARNING: daemon is not using the default seccomp pro`
- `Error response from daemon: Get "https://registry-1.docker.io/v2/": net/http: request canceled while waiting for connection (Client.Timeout exceeded while awaiting headers)`
