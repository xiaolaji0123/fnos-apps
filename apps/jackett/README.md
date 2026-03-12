# Jackett for fnOS

每日自动同步 [Jackett 官方](https://github.com/Jackett/Jackett) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=jackett) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:9117`

## 说明

- Torrent 索引器代理服务，为 Sonarr、Radarr 等提供统一搜索接口
- 支持数百个 BT 站点的聚合搜索
- 可配置为 *arr 系列工具的索引器源
- 首次启动无认证，请在设置中配置管理员密码
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_jackett.sh                        # 最新版本，自动检测架构
./update_jackett.sh --arch arm             # 指定架构
./update_jackett.sh --help                 # 查看帮助
```

## 版本标签

- `jackett/vX.Y.Z` — 首次发布
- `jackett/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Jackett](https://github.com/Jackett/Jackett)
