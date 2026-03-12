# Duplicati for fnOS

每日自动同步 [Duplicati 官方](https://duplicati.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=duplicati) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8200`

## 说明

- 加密备份工具，支持增量备份
- 支持备份到云存储和本地存储
- 支持压缩和 AES-256 加密
- 提供 Web UI 管理备份任务
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/duplicati && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Duplicati](https://duplicati.com)
