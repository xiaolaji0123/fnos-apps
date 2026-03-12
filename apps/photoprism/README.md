# PhotoPrism for fnOS

每日自动同步 [PhotoPrism 官方](https://photoprism.app) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=photoprism) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:2342`
**默认密码**: `admin`

## 说明

- AI 驱动的照片管理工具，支持人脸识别和场景分类
- 自动提取 EXIF 信息和地理位置数据
- 支持 RAW 格式预览和视频转码
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/photoprism && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [PhotoPrism](https://photoprism.app)
