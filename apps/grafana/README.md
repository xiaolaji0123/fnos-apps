# Grafana for fnOS

每日自动同步 [Grafana 官方](https://grafana.com) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=grafana) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:3010`

## 说明

- 开源可视化监控仪表盘平台
- 支持 Prometheus、Loki、InfluxDB 等多种数据源
- 丰富的图表类型和预置仪表盘模板
- 支持告警规则配置和通知推送
- 数据存储在应用数据目录中

## 本地构建

```bash
./update_grafana.sh                        # 最新版本，自动检测架构
./update_grafana.sh --arch arm             # 指定架构
./update_grafana.sh --help                 # 查看帮助
```

## 版本标签

- `grafana/vX.Y.Z` — 首次发布
- `grafana/vX.Y.Z-r2` — 同版本打包修订

## Credits

- [Grafana](https://grafana.com)
