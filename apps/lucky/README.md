# Lucky for fnOS

每日自动同步 [Lucky 官方](https://lucky666.cn) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=lucky) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:16601`

## 说明

- 多功能网络工具箱
- 支持 DDNS、反向代理、端口转发
- 内置 Web 防火墙与 SSL 证书管理
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_lucky.sh                         # 最新版本，自动检测架构
./update_lucky.sh --arch arm              # 指定架构
./update_lucky.sh --help                  # 查看帮助
```

## 版本标签

- `lucky/vX.Y.Z` — 首次发布
- `lucky/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Lucky](https://lucky666.cn)
