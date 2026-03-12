# ClamAV for fnOS

每日自动同步 [ClamAV 官方](https://github.com/Cisco-Talos/clamav) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=clamav) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3310`

## 说明

- 开源杀毒引擎，提供文件扫描服务
- 自动更新病毒特征库
- 支持 Web UI 管理和查看扫描结果
- 适合定期扫描 NAS 上的文件
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/clamav && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [ClamAV](https://github.com/Cisco-Talos/clamav)
