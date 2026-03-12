# SurveyKing for fnOS

每日自动同步 [SurveyKing 官方](https://github.com/anji-plus/survey) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=surveyking) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://&lt;NAS-IP&gt;:1991`

## 说明

- 开源问卷调查和在线考试系统，支持多种题型
- 提供可视化表单设计器和数据统计分析
- 支持逻辑跳转、限时考试和防作弊功能
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/surveyking && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [SurveyKing](https://github.com/anji-plus/survey)
