# Beszel for fnOS

每日自动同步 [Beszel 官方](https://github.com/henrygd/beszel) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=beszel) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:18090`

## 说明

- 轻量级服务器监控与告警系统
- 支持 CPU、内存、磁盘、网络流量监控
- 可配置多主机集中管理
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_beszel.sh                        # 最新版本，自动检测架构
./update_beszel.sh --arch arm             # 指定架构
./update_beszel.sh --help                 # 查看帮助
```

## 版本标签

- `beszel/vX.Y.Z` — 首次发布
- `beszel/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Beszel](https://github.com/henrygd/beszel)
