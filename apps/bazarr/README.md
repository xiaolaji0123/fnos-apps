# Bazarr for fnOS

每日自动同步 [Bazarr 官方](https://www.bazarr.media) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=bazarr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:6767`

## 说明

- 字幕自动化管理工具，与 Sonarr/Radarr 配合使用
- 自动搜索、下载并匹配电影和剧集字幕
- 支持多种字幕格式和语言
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/bazarr && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Bazarr](https://www.bazarr.media)
