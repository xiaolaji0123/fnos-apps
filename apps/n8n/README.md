# n8n for fnOS

每日自动同步 [n8n 官方](https://n8n.io) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=n8n) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:5678`

## 说明

- 工作流自动化工具，支持 400+ 集成
- 可视化编辑器，无需编程即可创建自动化流程
- 支持定时任务、Webhook 触发和数据转换
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/n8n && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [n8n](https://n8n.io)
