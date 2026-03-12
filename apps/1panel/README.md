# 1Panel for fnOS

每日自动同步 [1Panel 官方](https://1panel.cn) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=1panel) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:10086`

## 说明

- 开源的服务器运维管理面板，提供可视化的 Linux 服务器管理能力
- 支持网站管理、数据库管理、文件管理等一站式运维功能
- 内置应用商店，可快速安装常用服务
- 首次启动需要初始化配置管理员账号
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_1panel.sh                        # 最新版本，自动检测架构
./update_1panel.sh --arch arm             # 指定架构
./update_1panel.sh --help                 # 查看帮助
```

## 版本标签

- `1panel/vX.Y.Z` — 首次发布
- `1panel/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [1Panel](https://1panel.cn)
