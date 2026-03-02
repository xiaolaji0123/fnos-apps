# Nextcloud for fnOS

每日自动同步 [Nextcloud](https://nextcloud.com/) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=nextcloud) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8082`

## 说明

- Nextcloud 是开源私有云存储平台，类似 Google Drive/Dropbox 的自托管方案
- 支持文件同步、WebDAV、在线文档协作、日历和联系人管理
- 包含 3 个服务容器: Nextcloud (Apache)、MariaDB、Redis
- 首次启动需要拉取镜像，耗时较长

## 本地构建

```bash
cd apps/nextcloud && bash ../../scripts/build-fpk.sh . app.tgz
```

## 版本标签

- `nextcloud/v30.0.0` — 首次发布
- `nextcloud/v30.0.0-r2` — 同版本打包修订
