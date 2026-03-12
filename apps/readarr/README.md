# Readarr for fnOS

每日自动同步 [Readarr 官方](https://readarr.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=readarr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8787`

## 说明

- 电子书与有声书自动化管理工具
- *arr 生态成员，可与 Prowlarr、Sonarr、Radarr 联动
- 支持书籍元数据抓取与整理
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_readarr.sh                       # 最新版本，自动检测架构
./update_readarr.sh --arch arm            # 指定架构
./update_readarr.sh --help                # 查看帮助
```

## 版本标签

- `readarr/vX.Y.Z` — 首次发布
- `readarr/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Readarr](https://readarr.com)
