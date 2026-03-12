# Mattermost for fnOS

每日自动同步 [Mattermost 官方](https://mattermost.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=mattermost) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8065`

## 说明

- 企业级即时通讯平台，Slack 的开源替代方案
- 内置 PostgreSQL 数据库，开箱即用
- 支持团队消息、文件分享、语音视频通话
- 端到端加密，数据完全自主可控
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/mattermost && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Mattermost](https://mattermost.com)
