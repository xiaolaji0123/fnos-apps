# KodBox for fnOS

每日自动同步 [KodBox 官方](https://kodcloud.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=kodbox) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8500`

## 说明

- 私有云存储和在线文档协作平台
- 支持在线编辑 Office 文档、预览多种文件格式
- 多用户权限管理和文件共享
- 提供 WebDAV 接口，可作为网盘使用
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/kodbox && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [KodBox](https://kodcloud.com)
