# Pi-hole for fnOS

每日自动同步 [Pi-hole 官方](https://pi-hole.net) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=pihole) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8053`

## 说明

- 全网广告拦截 DNS 服务器
- 拦截广告、追踪器和恶意域名
- 需占用 53/tcp 和 53/udp 端口
- 请确保 NAS 上无其他 DNS 服务冲突
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/pihole && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Pi-hole](https://pi-hole.net)
