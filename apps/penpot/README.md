# Penpot for fnOS

每日自动同步 [Penpot 官方](https://github.com/penpot/penpot) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=penpot) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:9001`

## 说明

- 开源设计和原型工具，Figma 的开源替代方案
- 支持多人实时协作和组件库管理
- 基于 SVG 格式，可与 Inkscape 等工具互通
- 基于 Docker 部署，首次启动需要拉取镜像
- 包含 5 个服务容器: frontend, backend, exporter, PostgreSQL, Redis

## 本地构建

```bash
cd apps/penpot && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Penpot](https://github.com/penpot/penpot)
