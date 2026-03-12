# Nginx Proxy Manager for fnOS

每日自动同步 [Nginx Proxy Manager 官方](https://github.com/NginxProxyManager/nginx-proxy-manager) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=nginx-proxy-manager) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:81`

## 说明

- 反向代理可视化管理面板
- 一键配置 SSL 证书和 HTTPS 跳转
- 支持多域名、子域名和路径转发规则
- 默认登录：admin@example.com / changeme
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/nginx-proxy-manager && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager)
