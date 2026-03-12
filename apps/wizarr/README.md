# Wizarr for fnOS

每日自动同步 [Wizarr 官方](https://github.com/wizarrrr/wizarr) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=wizarr) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:5690`

## 说明

- Plex/Jellyfin 用户邀请管理工具
- 生成邀请链接，简化媒体库共享流程
- 支持自定义邀请过期时间和使用次数
- 新用户可通过邀请链接自助注册
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/wizarr && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Wizarr](https://github.com/wizarrrr/wizarr)
