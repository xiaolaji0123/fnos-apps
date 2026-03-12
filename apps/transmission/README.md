# Transmission for fnOS

每日自动同步 [Transmission 官方](https://transmissionbt.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=transmission) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:9091`

## 说明

- 轻量级 BitTorrent 客户端，资源占用极低
- 简洁的 Web 界面，支持远程管理
- 支持磁力链接、种子文件和 RSS 订阅
- 可设置速度限制、种子比率和自动清理
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/transmission && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Transmission](https://transmissionbt.com)
