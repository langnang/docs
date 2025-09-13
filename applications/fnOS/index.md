# fnOS

## 议题

### 盒盖不休眠

```sh
sudo vim /etc/systemd/logind.conf
```

将HandleLidSwitch的值从suspend改为ignore并将HandleLidSwitch、LidSwitchIgnoreInhibited前面的注释符号#删除。

保存完毕后输入（reboot），系统重启之后，重新将笔记本合盖测试，一切正常。
