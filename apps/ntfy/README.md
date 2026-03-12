# Ntfy for fnOS

每日自动同步 [Ntfy 官方](https://ntfy.sh) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=ntfy) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:2586`

## 说明

- 自托管推送通知服务，支持 HTTP 接口发送通知
- 可推送消息到手机、桌面浏览器等终端
- 支持 iOS 和 Android 原生客户端
- 无需注册账号，使用订阅主题即可接收通知
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_ntfy.sh                        # 最新版本，自动检测架构
./update_ntfy.sh --arch arm             # 指定架构
./update_ntfy.sh --help                 # 查看帮助
```

## 版本标签

- `ntfy/vX.Y.Z` — 首次发布
- `ntfy/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Ntfy](https://ntfy.sh)
