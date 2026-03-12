# Frigate for fnOS

每日自动同步 [Frigate 官方](https://frigate.video) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=frigate) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8971`

## 说明

- AI 视频监控系统，支持实时物体检测
- 支持本地处理，无需云端
- 提供录像回放和事件管理
- 建议启用 GPU 加速提升检测性能
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/frigate && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Frigate](https://frigate.video)
