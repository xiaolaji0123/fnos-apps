# Jellystat for fnOS

每日自动同步 [Jellystat 官方](https://github.com/CyferShepard/Jellystat) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=jellystat) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3004`

## 说明

- Jellyfin 使用统计与监控工具
- 可视化展示播放历史和用户活动
- 支持库统计和观看趋势分析
- 提供详细的媒体服务器报表
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/jellystat && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Jellystat](https://github.com/CyferShepard/Jellystat)
