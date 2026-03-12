# Linkwarden for fnOS

每日自动同步 [Linkwarden 官方](https://linkwarden.app) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=linkwarden) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:3050`

## 说明

- 协作式书签管理器，支持团队共享书签集合
- 自动抓取网页截图和存档，防止链接失效
- 支持标签分类、全文搜索和导入导出
- 基于 Docker 部署，首次启动需要拉取镜像
- 包含 2 个服务容器: Linkwarden 应用 + PostgreSQL 数据库

## 本地构建

```bash
cd apps/linkwarden && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Linkwarden](https://linkwarden.app)
