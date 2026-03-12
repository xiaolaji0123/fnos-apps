# Prowlarr for fnOS

每日自动同步 [Prowlarr 官方](https://prowlarr.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=prowlarr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:9696`

## 说明

- 索引器管理与代理工具
- *arr 生态核心组件，为 Sonarr、Radarr、Lidarr 提供索引支持
- 支持多种 Torrent 与 Usenet 索引器
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_prowlarr.sh                      # 最新版本，自动检测架构
./update_prowlarr.sh --arch arm           # 指定架构
./update_prowlarr.sh --help               # 查看帮助
```

## 版本标签

- `prowlarr/vX.Y.Z` — 首次发布
- `prowlarr/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Prowlarr](https://prowlarr.com)
