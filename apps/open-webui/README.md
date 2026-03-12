# Open WebUI for fnOS

每日自动同步 [Open WebUI 官方](https://github.com/open-webui/open-webui) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=open-webui) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:8080`

## 说明

- AI 聊天界面，支持 Ollama、OpenAI 等多模型对话
- 类 ChatGPT 体验，支持多轮对话和历史记录
- 可对接本地 Ollama 实例或远程 API
- 支持 RAG 文档问答和模型参数调整
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/open-webui && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Open WebUI](https://github.com/open-webui/open-webui)
