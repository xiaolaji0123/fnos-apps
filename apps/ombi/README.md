# Ombi for fnOS

每日自动同步 [Ombi 官方](https://github.com/Ombi-app/Ombi) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=ombi) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3579`

## 说明

- 媒体请求与用户管理工具，用户可自助申请添加影片
- 支持对接 Plex、Emby、Jellyfin 等媒体服务器
- 自动将请求转发至 Sonarr/Radarr 进行下载
- 内置用户权限管理和通知功能
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/ombi && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Ombi](https://github.com/Ombi-app/Ombi)
