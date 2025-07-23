![](./badge.png)



<div align="center">
  <h1>🚀 A1 - 数据库原生热插拔AI中台</h1>
</div>

<p align="center">
    <a href="https://unisudo.com" target="_blank">
        <img alt="Static Badge" src="https://img.shields.io/badge/Product-F04438"></a>
    <a href="https://unisudo.com/pricing" target="_blank">
        <img alt="Static Badge" src="https://img.shields.io/badge/free-pricing?logo=free&color=%20%23155EEF&label=pricing&labelColor=%20%23528bff"></a>
    <a href="https://twitter.com/intent/follow?screen_name=unisudo_ai" target="_blank">
        <img src="https://img.shields.io/twitter/follow/unisudo_ai?logo=X&color=%20%23f5f5f5"
            alt="follow on X(Twitter)"></a>
    <a href="https://hub.docker.com/u/unisudo" target="_blank">
        <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/unisudo/unisudo-ai?labelColor=%20%23FDB062&color=%20%23f79009"></a>
    <a href="https://github.com/UniSudo-Inc/marker/graphs/commit-activity" target="_blank">
        <img alt="Commits last month" src="https://img.shields.io/github/commit-activity/m/UniSudo-Inc/marker?labelColor=%20%2332b583&color=%20%2312b76a"></a>
</p>

点击切换语言
<div align="center">
  <a href="./README.md"><img alt="README in English" src="https://img.shields.io/badge/English-2222FF"></a>
  <a href="./README_CN.md"><img alt="简体中文版自述文件" src="https://img.shields.io/badge/简体中文-FF2222"></a>
    <a href="./README_AR.md"><img alt="العربية" src="https://img.shields.io/badge/العربية-00"></a>
</div>

A1 是一个完全自主可控的 AI 应用开发平台，专为企业级离线部署而设计。与其他平台不同，UniSudo AI 实现了真正的"全栈离线"，所有组件都可以在完全断网的环境下运行，确保数据安全与隐私保护。

**🌟 我们的核心优势**

**1. 唯一全离线支持** 🔒
  - 支持所有组件完全离线一体部署
  - 无需联网即可完成模型推理、文档处理、向量化等全流程
  - 支持所有主流文档格式的智能切分与处理

**2. 深度数据库集成** 🗄️
  - 唯一与数据库深度绑定的数据驱动执行引擎
  - 原生支持多种数据库连接与查询优化
  - 实时数据分析与智能决策支持

**3. 流式工作流引擎** ⚡
  - 唯一支持流式聊天、Agent驱动的协同工作系统
  - 实时响应，无延迟的交互体验
  - 多Agent协作，打造真正的AI团队

**4. 完全自主部署** 🏗️
  - 唯一可全流程自主部署的AI中台
  - 支持私有云、混合云等多种部署模式
  - 完整的企业级安全与权限管理


## 核心功能

**1. 智能工作流引擎**: 
  可视化流程设计，支持复杂业务逻辑的AI自动化处理

**2. 全模型支持**: 
  支持国产大模型（文心一言、通义千问、ChatGLM等）及开源模型的完全离线部署

**3. 企业级RAG**: 
  支持PDF、Word、PPT、Excel等所有办公文档格式的智能解析与检索

**4. Multi-Agent系统**: 
  多智能体协作，构建企业级AI助手团队

**5. 数据安全保障**: 
  企业数据永不出域，完全符合数据安全法规要求

**6. 一键部署**: 
  Docker容器化部署，5分钟完成私有化部署
## 产品对比
<table style="width: 100%;">
  <tr>
    <th align="center">功能特性</th>
    <th align="center">UniSudo AI</th>
    <th align="center">Dify</th>
    <th align="center">LangChain</th>
    <th align="center">其他平台</th>
  </tr>
  <tr>
    <td align="center">完全离线部署</td>
    <td align="center">✅ 真正离线</td>
    <td align="center">❌ 需要联网</td>
    <td align="center">❌ 需要联网</td>
    <td align="center">❌ 需要联网</td>
  </tr>
  <tr>
    <td align="center">数据库深度集成</td>
    <td align="center">✅ 原生支持</td>
    <td align="center">⚠️ 基础支持</td>
    <td align="center">⚠️ 需要开发</td>
    <td align="center">❌ 不支持</td>
  </tr>
  <tr>
    <td align="center">流式工作流</td>
    <td align="center">✅ 实时流式</td>
    <td align="center">⚠️ 基础工作流</td>
    <td align="center">❌ 不支持</td>
    <td align="center">❌ 不支持</td>
  </tr>
  <tr>
    <td align="center">国产模型优化</td>
    <td align="center">✅ 深度优化</td>
    <td align="center">⚠️ 基础支持</td>
    <td align="center">⚠️ 需要配置</td>
    <td align="center">❌ 不支持</td>
  </tr>
  <tr>
    <td align="center">一键部署</td>
    <td align="center">✅ 5分钟部署</td>
    <td align="center">⚠️ 需要配置</td>
    <td align="center">❌ 复杂部署</td>
    <td align="center">❌ 复杂部署</td>
  </tr>
</table>

## 快速开始
### 系统要求
- CPU >= 4 Core (推荐 8 Core)
- RAM >= 8 GiB (推荐 16 GiB)
- GPU >= NVIDIA A10G (或同等性能)
- 硬盘 >= 500 GB (SSD推荐)
- Docker >= 20.10
- Docker Compose >= 2.0
### 一键部署
```bash
# 克隆项目
git clone https://github.com/UniSudo-Inc/marker.git
cd marker
# 启动服务
docker-compose up -d
# 访问服务
open http://localhost:3000
```

## 应用场景
### 🏢 企业知识管理
- 内部文档智能问答
- 知识库自动构建
- 专业领域AI助手
### 🔍 数据分析平台
- 业务数据智能分析
- 报表自动生成
- 决策支持系统
### 🤖 客服机器人
- 7x24小时智能客服
- 多轮对话支持
- 业务流程自动化
### 🎯 定制化AI应用
- 行业专用AI工具
- 垂直领域解决方案
- 私有化AI服务
## 部署选项
### 🌤️ 云端部署
- **UniSudo Cloud 🏗️**: 托管版本，开箱即用
- **私有云**: 支持阿里云、腾讯云、华为云等
- **混合云**: 云端管理，本地执行
### 🏠 本地部署
- **Docker部署**: 单机或集群部署
- **Kubernetes**: 企业级容器编排
- **物理机**: 直接安装，性能最优
### 📦 离线部署
- **完全断网**: 支持完全离线环境
- **内网部署**: 企业内网专用版本
- **边缘计算**: 支持边缘设备部署
## 开发路线图
### v0.4.0 (先行版)
- ✅ 基础工作流引擎
- ✅ RAG文档处理
- ✅ 基础Agent功能
- ✅ 离线部署支持
### v1.0 (2025 Q4)
- 🔄 多模态支持 (图像、语音、视频)
- 🔄 高级工作流节点
- 🔄 企业级权限管理
- 🔄 API市场
### v1.1 (2026 Q1)
- 📋 自动化测试平台
- 📋 可视化监控大屏
- 📋 多租户架构
- 📋 国际化支持
### v2.0 (2026 Q3)
- 📋 分布式集群部署
- 📋 AI模型训练平台
- 📋 插件生态系统
- 📋 边缘计算支持
## 社区与支持
### 🤝 加入社区
- [GitHub讨论区](https://github.com/UniSudo-Inc/a1/discussions) - 技术交流与产品反馈
- [微信群]() - 扫码加入官方微信群

### 📧 商务合作
- 企业版咨询: contact@unisudo.com
- 技术支持: developer@unisudo.com
- 媒体联系: social@unisudo.com
- 客户支持: support@unisudo.com

### 🐛 问题反馈
- [GitHub Issues](https://github.com/UniSudo-Inc/marker/issues) - Bug反馈与功能建议
- [安全问题](mailto:developer@unisudo.com) - 安全漏洞报告

### 其他贡献方式
- 📝 改进文档
- 🐛 报告Bug
- 💡 提出新功能建议
- 🌍 帮助翻译
- 📢 推广宣传
---
<div align="center">
  <h3>🌟 如果这个项目对您有帮助，请给我们一个 Star！🌟</h3>

  **让AI真正为中国企业服务**

  [⭐ Star](https://github.com/UniSudo-Inc/marker) | [🍴 Fork](https://github.com/UniSudo-Inc/marker/fork) | [📖 文档](https://docs.unisudo.com) | [💬 交流群](https://chat.unisudo.com)
</div>