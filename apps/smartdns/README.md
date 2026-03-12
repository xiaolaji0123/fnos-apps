# SmartDNS for fnOS

每日自动同步 [SmartDNS 官方](https://github.com/pymumu/smartdns) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=smartdns) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:6580`

## 说明

- 本地 DNS 服务器，加速域名解析
- 支持多上游 DNS 优选与缓存
- DNS 端口可配置，默认 6580 为管理界面
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_smartdns.sh                      # 最新版本，自动检测架构
./update_smartdns.sh --arch arm           # 指定架构
./update_smartdns.sh --help               # 查看帮助
```

## 版本标签

- `smartdns/vX.Y.Z` — 首次发布
- `smartdns/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [SmartDNS](https://github.com/pymumu/smartdns)
