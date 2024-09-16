502G

```shell
apt_repo="deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] $DOWNLOAD_URL/linux/$lsb_dist bookworm $CHANNEL"
```
