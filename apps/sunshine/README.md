# Sunshine for fnOS

每日自动同步 [Sunshine 官方](https://docs.lizardbyte.dev/projects/sunshine/) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=sunshine) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:47990`

## 说明

- 游戏串流服务器，配合 Moonlight 客户端远程游戏
- 支持硬件编码（NVENC、VAAPI、AMF）
- 低延迟视频传输，支持 4K HDR 串流
- 支持手柄、键鼠远程输入
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/sunshine && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Sunshine](https://docs.lizardbyte.dev/projects/sunshine/)
