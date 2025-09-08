# NVIDIA NeMo Agent Toolkit——Agentic AI 应用

> 🏆 **黑客松项目** - 基于NVIDIA官方NeMo Agent Toolkit构建的智能对话机器人，展示AI Agent的强大功能

## 🎯 项目简介

本项目是完全基于官方提供的基础项目（https://github.com/HeKun-NVIDIA/hackathon_aiqtoolkit/tree/main）
，进行优化构建后的产出项目应用。

> **功能模块和技术亮点，详见提交的项目文档等资料**。

## 🚀 项目部署

### 📋 环境要求

- **Python**: 3.12+
- **Node.js**: 18+
- **Git**: 最新版本
- **操作系统**: Windows 10+/macOS 10.15+/Ubuntu 20.04+
- **环境依赖**: ./requirements.txt

### 🎮 启动系统

```bash
# 启动服务
cd NeMo-Agent-Toolkit
./start.sh

# 停止服务
./stop.sh
```

### 🌐 访问地址

- **前端界面**: http://localhost:3000
- **API文档**: http://localhost:8001/docs
- **健康检查**: http://localhost:8001/health

## 📁 项目核心代码

### Config配置
./hackathon_aiqtoolkit_agent/NeMo-Agent-Toolkit/configs/hackathon_config.yml

### MCP工具
./hackathon_aiqtoolkit_agent/NeMo-Agent-Toolkit/src/nat/tool
./hackathon_aiqtoolkit_agent/packages/aiqtoolkit_langchain/src/aiq/plugins/langchain/tools/tavily_internet_search.py

### Knowledge Docs
./hackathon_aiqtoolkit_agent/NeMo-Agent-Toolkit/src/nat/tool/data


## 📚 相关资源

### 官方文档
- [NVIDIA NeMo Agent Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit)
- [官方文档](https://docs.nvidia.com/nemo-agent-toolkit/)
- [NeMo Agent Toolkit UI](https://github.com/NVIDIA/NeMo-Agent-Toolkit-UI)

### API文档
- [Tavily API文档](https://docs.tavily.com/)
- [阿里云百炼平台](https://bailian.console.aliyun.com/?tab=doc#/doc)
- [OpenAI API文档](https://platform.openai.com/docs/)

### 学习资源
- [AI Agent开发指南](https://docs.nvidia.com/nemo-agent-toolkit/user-guide/)
- [React Agent工作流](https://docs.nvidia.com/nemo-agent-toolkit/workflows/react-agent/)
- [MCP协议文档](https://docs.nvidia.com/nemo-agent-toolkit/mcp/)

## 🏆 黑客松信息

本项目专为推广NVIDIA NeMo Agent Toolkit技术而开发，旨在：

- 🎯 **展示AI Agent能力**: 通过实际应用展示NVIDIA NeMo Agent Toolkit的强大功能
- 🚀 **降低学习门槛**: 提供完整的示例代码和详细文档，帮助开发者快速上手
- 🌟 **促进技术交流**: 为AI Agent技术爱好者提供学习和交流的平台
- 💡 **激发创新思维**: 鼓励开发者基于此项目创建更多创新应用

### 技术亮点

- ✅ **完全官方架构**: 严格遵循NVIDIA官方技术规范
- ✅ **生产级质量**: 包含完整的错误处理、日志记录和监控
- ✅ **易于扩展**: 模块化设计，支持快速添加新功能
- ✅ **跨平台支持**: 一套代码，多平台运行



---

**🎯 让我们一起探索AI Agent的无限可能！**

> 本项目展示了NVIDIA NeMo Agent Toolkit在实际应用中的强大能力，为AI Agent技术的普及和发展贡献力量。
