# Bililive-go for fnOS

每日自动同步 [Bililive-go 官方](https://github.com/bililive-go/bililive-go) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=bililive-go) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8680`

## 说明

- 支持 B站、斗鱼、虎牙等多平台直播录制
- 可配置自动录制与定时任务
- 支持录制质量选择与文件分割
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_bililive-go.sh                   # 最新版本，自动检测架构
./update_bililive-go.sh --arch arm        # 指定架构
./update_bililive-go.sh --help            # 查看帮助
```

## 版本标签

- `bililive-go/vX.Y.Z` — 首次发布
- `bililive-go/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Bililive-go](https://github.com/bililive-go/bililive-go)
