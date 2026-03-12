# Radarr for fnOS

每日自动同步 [Radarr 官方](https://radarr.video) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=radarr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:7878`

## 说明

- 电影自动化下载与管理工具
- *arr 生态成员，可与 Prowlarr、Sonarr 联动
- 支持多种下载客户端集成
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_radarr.sh                        # 最新版本，自动检测架构
./update_radarr.sh --arch arm             # 指定架构
./update_radarr.sh --help                 # 查看帮助
```

## 版本标签

- `radarr/vX.Y.Z` — 首次发布
- `radarr/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Radarr](https://radarr.video)
