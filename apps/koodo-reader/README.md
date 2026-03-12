# Koodo Reader for fnOS

每日自动同步 [Koodo Reader 官方](https://github.com/koodo-reader/koodo-reader) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=koodo-reader) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8930`

## 说明

- 现代电子书管理器与阅读器
- 支持 EPUB、PDF、Mobi、CBZ 等多种格式
- 内置书签、笔记、高亮标注功能
- 支持跨平台阅读进度同步
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/koodo-reader && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Koodo Reader](https://github.com/koodo-reader/koodo-reader)
