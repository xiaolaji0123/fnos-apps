# Certimate for fnOS

每日自动同步 [Certimate 官方](https://github.com/usual2970/certimate) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=certimate) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8090`

## 说明

- SSL/TLS 证书自动化管理工具，支持 ACME 协议
- 自动申请和续签 Let's Encrypt、ZeroSSL 等证书
- 支持阿里云、腾讯云、Cloudflare 等多种 DNS 验证
- 可自动部署证书到 Nginx、CDN 等服务
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_certimate.sh                        # 最新版本，自动检测架构
./update_certimate.sh --arch arm             # 指定架构
./update_certimate.sh --help                 # 查看帮助
```

## 版本标签

- `certimate/vX.Y.Z` — 首次发布
- `certimate/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Certimate](https://github.com/usual2970/certimate)
