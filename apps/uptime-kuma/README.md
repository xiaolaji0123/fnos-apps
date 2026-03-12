# Uptime Kuma for fnOS

每日自动同步 [Uptime Kuma 官方](https://github.com/louislam/uptime-kuma) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=uptime-kuma) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:3001`

## 说明

- 服务可用性监控工具，支持 HTTP/HTTPS/TCP/Ping 等多种检测方式
- 实时监控网站状态，故障时通过多种渠道发送告警
- 支持状态页面发布，对外展示服务运行状况
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/uptime-kuma && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Uptime Kuma](https://github.com/louislam/uptime-kuma)
