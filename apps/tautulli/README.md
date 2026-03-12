# Tautulli for fnOS

每日自动同步 [Tautulli 官方](https://tautulli.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=tautulli) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8181`

## 说明

- Plex 使用统计与监控工具
- 实时查看谁在观看什么内容
- 支持观看历史、热门内容和通知推送
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/tautulli && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Tautulli](https://tautulli.com)
