# DPanel for fnOS

每日自动同步 [DPanel 官方](https://github.com/donknap/dpanel) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=dpanel) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8807`

## 说明

- 轻量级 Docker 可视化管理面板
- 支持容器管理和镜像操作
- 提供 Compose 编排功能
- 界面简洁，资源占用低
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/dpanel && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [DPanel](https://github.com/donknap/dpanel)
