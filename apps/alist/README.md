# Alist for fnOS

每日自动同步 [Alist 官方](https://github.com/AlistGo/alist) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=alist) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:5246`

## 说明

- 网盘聚合工具，支持挂载阿里云盘、百度网盘等多种网络存储
- 统一管理多个网盘账号，提供统一的文件浏览和下载入口
- 支持 WebDAV 协议，可作为 WebDAV 服务器使用
- 首次启动会生成初始密码，请查看日志获取
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_alist.sh                        # 最新版本，自动检测架构
./update_alist.sh --arch arm             # 指定架构
./update_alist.sh --help                 # 查看帮助
```

## 版本标签

- `alist/vX.Y.Z` — 首次发布
- `alist/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Alist](https://github.com/AlistGo/alist)
