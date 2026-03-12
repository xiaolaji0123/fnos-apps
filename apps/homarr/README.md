# Homarr for fnOS

每日自动同步 [Homarr 官方](https://homarr.dev) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=homarr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:7575`

## 说明

- 可视化应用仪表盘，集成多种服务
- 支持应用状态监控和实时数据展示
- 内置搜索栏、日历、天气等小组件
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/homarr && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Homarr](https://homarr.dev)
