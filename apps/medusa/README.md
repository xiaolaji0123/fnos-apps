# Medusa for fnOS

每日自动同步 [Medusa 官方](https://github.com/pymedusa/Medusa) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=medusa) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8081`

## 说明

- 电视剧自动化下载管理工具
- 自动搜索、下载和整理最新剧集
- 支持多种索引器和下载客户端集成
- 可自定义视频质量和字幕语言偏好
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/medusa && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Medusa](https://github.com/pymedusa/Medusa)
