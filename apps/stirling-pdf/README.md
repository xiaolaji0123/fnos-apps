# Stirling-PDF for fnOS

每日自动同步 [Stirling-PDF 官方](https://stirlingpdf.io) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=stirling-pdf) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:18080`

## 说明

- 本地 PDF 工具箱，支持 50+ 种 PDF 操作
- 支持合并、拆分、压缩、转换、OCR 识别等功能
- 完全本地处理，保护文档隐私
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/stirling-pdf && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Stirling-PDF](https://stirlingpdf.io)
