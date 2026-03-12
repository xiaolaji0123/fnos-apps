# Ollama for fnOS

每日自动同步 [Ollama 官方](https://github.com/ollama/ollama) 最新版本并构建 `.fpk` 安装包。

## 下载

从 [Releases](https://github.com/conversun/fnos-apps/releases?q=ollama) 下载最新的 `.fpk` 文件。

## 安装

1. 根据设备架构下载对应的 `.fpk` 文件
2. fnOS 应用管理 → 手动安装 → 上传

**访问地址**: `http://<NAS-IP>:11434`

## 说明

- 本地大语言模型运行引擎，一键拉取和运行开源 LLM
- 支持 Llama、Mistral、Gemma、Qwen 等主流模型
- 提供 OpenAI 兼容 API，可搭配 Open WebUI 使用
- 模型文件持久化存储，重启后自动加载
- 基于 Docker 部署，首次启动需要拉取镜像

## 本地构建

```bash
cd apps/ollama && bash ../../scripts/build-fpk.sh . app.tgz
```

## Credits

- [Ollama](https://github.com/ollama/ollama)
