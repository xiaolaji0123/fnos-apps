# Navidrome for fnOS

每日自动同步 [Navidrome 官方](https://www.navidrome.org) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=navidrome) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:4533`

## 说明

- 开源个人音乐流媒体服务器，兼容 Subsonic/Airsonic API
- 支持多种音频格式，内置转码功能
- 多用户支持，现代化 Web 界面
- 可配合 DSub、Symfonium 等移动客户端使用
- 安装后需在 fnOS 数据共享中配置音乐文件夹
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_navidrome.sh                        # 最新版本，自动检测架构
./update_navidrome.sh --arch arm             # 指定架构
./update_navidrome.sh --help                 # 查看帮助
```

## 版本标签

- `navidrome/vX.Y.Z` — 首次发布
- `navidrome/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Navidrome](https://www.navidrome.org)
