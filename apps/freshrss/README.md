# FreshRSS for fnOS

每日自动同步 [FreshRSS 官方](https://github.com/FreshRSS/FreshRSS) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=freshrss) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:8180`

## 说明

- 自托管 RSS 阅读器，界面简洁响应快速
- 支持 Fever API 和 Google Reader API，兼容多种客户端
- 提供文章过滤、标签管理和导入导出功能
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/freshrss && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [FreshRSS](https://github.com/FreshRSS/FreshRSS)
