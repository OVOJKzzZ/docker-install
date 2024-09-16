502G

```shell
apt_repo="deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] $DOWNLOAD_URL/linux/$lsb_dist <bookworm> $CHANNEL"
```
---------

当 Debian 新的稳定版发布时，应更改
```txt
/etc/apt/sources.list.d/docker.list
```
文件内的 Debian 版本代号。请先检查 docker-install.sh 脚本是否支持新的稳定版
