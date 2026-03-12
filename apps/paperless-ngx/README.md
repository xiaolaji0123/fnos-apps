# Paperless-ngx for fnOS

每日自动同步 [Paperless-ngx 官方](https://docs.paperless-ngx.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=paperless-ngx) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:8000`

## 说明

- 文档 OCR 扫描与归档管理系统，支持全文检索
- 自动识别发票、合同、证件等文档内容
- 支持标签、 correspondent 分类和自定义元数据
- 基于 Docker 部署，首次启动需要拉取镜像
- 包含 2 个服务容器: Paperless-ngx 应用 + Redis 缓存

## 本地构建

```bash
cd apps/paperless-ngx && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Paperless-ngx](https://docs.paperless-ngx.com)
