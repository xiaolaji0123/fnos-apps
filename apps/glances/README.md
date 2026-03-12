# Glances for fnOS

每日自动同步 [Glances 官方](https://nicolargo.github.io/glances/) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=glances) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:61208`

## 说明

- 系统监控，Web UI 版 htop
- 实时监控 CPU、内存、磁盘和网络
- 支持容器和进程详细信息
- 可配置告警通知
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/glances && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Glances](https://nicolargo.github.io/glances/)
