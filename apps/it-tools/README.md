# IT-Tools for fnOS

每日自动同步 [IT-Tools 官方](https://it-tools.tech) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=it-tools) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8280`

## 说明

- 开发者工具箱，包含 100+ 实用工具
- 支持编码转换、正则测试、JSON 格式化等功能
- 完全本地运行，无需联网
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/it-tools && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [IT-Tools](https://it-tools.tech)
