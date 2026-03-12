# NetBird for fnOS

每日自动同步 [NetBird 官方](https://netbird.io) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=netbird) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8820`

## 说明

- 零信任 VPN 管理平台
- 基于 WireGuard 的私有网络组建
- 客户端模式运行，使用 host 网络
- 支持多设备安全互联，无需公网 IP
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/netbird && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [NetBird](https://netbird.io)
