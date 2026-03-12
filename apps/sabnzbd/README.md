# SABnzbd for fnOS

每日自动同步 [SABnzbd 官方](https://github.com/sabnzbd/sabnzbd) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=sabnzbd) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8780`

## 说明

- Usenet 二进制新闻组下载客户端
- 支持自动解压、修复和后处理
- 可与 Sonarr、Radarr 等联动
- 界面简洁，下载速度高效稳定
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/sabnzbd && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [SABnzbd](https://github.com/sabnzbd/sabnzbd)
