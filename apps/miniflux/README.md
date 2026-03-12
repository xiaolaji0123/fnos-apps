# Miniflux for fnOS

每日自动同步 [Miniflux 官方](https://miniflux.app) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=miniflux) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:8190`
**默认账号**: `admin` / `admin`

## 说明

- 极简 RSS 阅读器，专注阅读体验无干扰
- 支持 Fever API，兼容 Reeder 等第三方客户端
- 内置全文抓取、内容过滤和自动归档功能
- 基于 Docker 部署，首次启动需要拉取镜像
- 包含 2 个服务容器: Miniflux 应用 + PostgreSQL 数据库

## 本地构建

```bash
cd apps/miniflux && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Miniflux](https://miniflux.app)
