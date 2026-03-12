# Tailscale for fnOS

每日自动同步 [Tailscale 官方](https://github.com/tailscale/tailscale) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=tailscale) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8088`

## 说明

- 基于 WireGuard 的零配置 Mesh VPN 客户端
- 无需公网 IP，设备间直连加密通信
- 支持 MagicDNS 自动域名解析
- 一键组网，适合远程访问 NAS 资源
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/tailscale && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Tailscale](https://github.com/tailscale/tailscale)
