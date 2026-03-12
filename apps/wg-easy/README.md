# WG-Easy for fnOS

每日自动同步 [WG-Easy 官方](https://github.com/wg-easy/wg-easy) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=wg-easy) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:51821`

## 说明

- WireGuard VPN 可视化管理界面
- 一键创建和管理 VPN 客户端配置
- 支持二维码扫描导入客户端配置
- 需要 `NET_ADMIN` 和 `SYS_MODULE` 容器权限，占用 `51820/udp` 端口
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/wg-easy && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [WG-Easy](https://github.com/wg-easy/wg-easy)
