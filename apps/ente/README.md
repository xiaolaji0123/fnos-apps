# Ente for fnOS

每日自动同步 [Ente 官方](https://ente.io) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=ente) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8510`

## 说明

- 端到端加密照片备份服务
- Google Photos 的隐私替代方案
- 客户端和服务器完全开源
- 支持 iOS、Android、Web 多平台
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/ente && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Ente](https://ente.io)
