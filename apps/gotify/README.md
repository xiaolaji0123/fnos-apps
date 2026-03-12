# Gotify for fnOS

每日自动同步 [Gotify 官方](https://gotify.net) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=gotify) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8070`

## 说明

- 自托管推送通知服务器，支持 REST API
- 提供 Web UI 管理应用和消息
- 支持 Android 客户端实时推送
- 可与其他服务集成实现告警通知
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_gotify.sh                        # 最新版本，自动检测架构
./update_gotify.sh --arch arm             # 指定架构
./update_gotify.sh --help                 # 查看帮助
```

## 版本标签

- `gotify/vX.Y.Z` — 首次发布
- `gotify/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Gotify](https://gotify.net)
