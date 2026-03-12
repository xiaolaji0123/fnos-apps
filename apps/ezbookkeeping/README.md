# EZBookkeeping for fnOS

每日自动同步 [EZBookkeeping 官方](https://github.com/mayswind/ezbookkeeping) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=ezbookkeeping) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8580`

## 说明

- 轻量级个人记账与财务管理工具
- 支持多币种与收支分类统计
- 提供图表分析与数据导出功能
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_ezbookkeeping.sh                 # 最新版本，自动检测架构
./update_ezbookkeeping.sh --arch arm      # 指定架构
./update_ezbookkeeping.sh --help          # 查看帮助
```

## 版本标签

- `ezbookkeeping/vX.Y.Z` — 首次发布
- `ezbookkeeping/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [EZBookkeeping](https://github.com/mayswind/ezbookkeeping)
