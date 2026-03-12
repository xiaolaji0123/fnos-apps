# AutoBangumi for fnOS

每日自动同步 [AutoBangumi 官方](https://github.com/EstrellaXD/Auto_Bangumi) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=auto-bangumi) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:7892`

## 说明

- 全自动追番下载整理工具
- 支持 Mikan Project 等主流动漫数据源
- 自动下载并重命名为 Plex/Jellyfin 兼容格式
- 需配合 qBittorrent 等下载工具使用
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/auto-bangumi && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [AutoBangumi](https://github.com/EstrellaXD/Auto_Bangumi)
