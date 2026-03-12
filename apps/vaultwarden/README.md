# Vaultwarden for fnOS

每日自动同步 [Vaultwarden 官方](https://github.com/dani-garcia/vaultwarden) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=vaultwarden) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:8880`

## 说明

- 密码管理器，与 Bitwarden 客户端完全兼容
- 支持自动填充、密码生成和安全笔记
- 端到端加密，数据完全存储在本地 NAS
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/vaultwarden && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Vaultwarden](https://github.com/dani-garcia/vaultwarden)
