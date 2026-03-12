# Jellyseerr for fnOS

每日自动同步 [Jellyseerr 官方](https://github.com/Fallenbagel/jellyseerr) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=jellyseerr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:5055`

## 说明

- 媒体请求管理工具，支持 Jellyfin/Emby/Plex
- 用户可请求电影和剧集，管理员审批后自动添加
- 与 Radarr/Sonarr 集成实现自动下载
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/jellyseerr && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Jellyseerr](https://github.com/Fallenbagel/jellyseerr)
