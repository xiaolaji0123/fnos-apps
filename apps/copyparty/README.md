# CopyParty for fnOS

每日自动同步 [CopyParty 官方](https://github.com/9001/copyparty) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=copyparty) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3923`

## 说明

- 便携文件共享服务器
- 支持拖拽上传和批量下载
- 内置 WebDAV 服务和文件搜索
- 支持视频转码和音乐播放
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/copyparty && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [CopyParty](https://github.com/9001/copyparty)
