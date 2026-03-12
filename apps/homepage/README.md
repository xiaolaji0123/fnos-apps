# Homepage for fnOS

每日自动同步 [Homepage 官方](https://gethomepage.dev) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=homepage) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3003`

## 说明

- 高度可定制的应用仪表盘，支持 YAML 配置
- 自动检测 Docker 容器状态并展示
- 支持多种服务集成和自定义小组件
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/homepage && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Homepage](https://gethomepage.dev)
