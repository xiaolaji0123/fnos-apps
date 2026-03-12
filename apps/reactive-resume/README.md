# Reactive Resume for fnOS

每日自动同步 [Reactive Resume 官方](https://github.com/amruthpillai/reactive-resume) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=reactive-resume) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3200`

## 说明

- 在线简历制作工具
- 多种精美模板可选，支持实时预览
- 可导出为 PDF、JSON 等格式
- 数据本地存储，隐私安全
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/reactive-resume && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Reactive Resume](https://github.com/amruthpillai/reactive-resume)
