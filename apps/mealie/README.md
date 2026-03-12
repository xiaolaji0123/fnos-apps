# Mealie for fnOS

每日自动同步 [Mealie 官方](https://mealie.io) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=mealie) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:9925`

## 说明

- 自托管食谱管理工具，支持 URL 自动抓取
- 可导入网页食谱并自动解析食材和步骤
- 支持膳食计划、购物清单和多人协作
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/mealie && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Mealie](https://mealie.io)
