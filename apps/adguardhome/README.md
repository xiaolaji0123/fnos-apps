# AdGuardHome for fnOS

每日自动同步 [AdGuardHome 官方](https://adguard.com/adguard-home/overview.html) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=adguardhome) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3080`

## 说明

- 全网广告拦截与 DNS 管理工具
- 支持 DNS-over-HTTPS 和 DNS-over-TLS
- 提供详细的查询统计和日志分析
- 可自定义过滤规则和Hosts
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/adguardhome && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [AdGuardHome](https://adguard.com/adguard-home/overview.html)
