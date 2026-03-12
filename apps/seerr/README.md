# Seerr for fnOS

每日自动同步 [Seerr 官方](https://github.com/seerr-team/seerr) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=seerr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:5055`

## 说明

- Overseerr 社区分支，媒体请求管理工具
- 支持 Plex/Jellyfin/Emby 媒体库集成
- 用户友好的界面管理电影和剧集请求
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/seerr && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Seerr](https://github.com/seerr-team/seerr)
