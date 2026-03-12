# Cloudflare Tunnel for fnOS

每日自动同步 [Cloudflare Tunnel 官方](https://github.com/WisdomSky/Cloudflared-web) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=cloudflared) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:14333`

## 说明

- 内网穿透隧道，无需公网 IP
- 通过 Cloudflare 网络实现安全访问
- 提供 Web UI 管理 Tunnel 配置
- 适合远程访问 NAS 上的服务
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/cloudflared && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Cloudflare Tunnel](https://github.com/WisdomSky/Cloudflared-web)
