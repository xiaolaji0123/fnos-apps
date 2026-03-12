# FileBrowser for fnOS

每日自动同步 [FileBrowser 官方](https://filebrowser.org) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=filebrowser) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8082`

## 说明

- 轻量级网页文件管理器
- 支持文件上传、下载、预览与编辑
- 可配置用户权限与访问范围
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_filebrowser.sh                   # 最新版本，自动检测架构
./update_filebrowser.sh --arch arm        # 指定架构
./update_filebrowser.sh --help            # 查看帮助
```

## 版本标签

- `filebrowser/vX.Y.Z` — 首次发布
- `filebrowser/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [FileBrowser](https://filebrowser.org)
