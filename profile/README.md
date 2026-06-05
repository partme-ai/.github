# PartMe AI

[![Stars](https://img.shields.io/github/stars/partme-ai/full-stack-skills?style=social)](https://github.com/partme-ai/full-stack-skills)
[![Repos](https://img.shields.io/badge/Repos-40+-blue?style=flat-square)](https://github.com/orgs/partme-ai/repositories)
[![Agent Skills](https://img.shields.io/badge/Agent_Skills-454-orange?style=flat-square)](https://github.com/full-statck-skills)
[![License](https://img.shields.io/badge/License-Apache_2.0-green?style=flat-square)](https://github.com/partme-ai/.github/blob/main/LICENSE)

**学习AI、掌握AI、聚焦智能体驱动（Agent-driven）的应用开发与落地，传播与AI有关的技术实践。**

> LLMs · 提示工程 · 函数调用 · RAG & Embeddings · Agents · MCP 协议 · Agent Skills · Agent Loop · 多智能体协作 · LLMs Tools · 模型微调

---

## 关于我们

PartMe AI 是一个专注于 AI 智能体生态的技术组织，致力于：

- **Agent Skills 体系建设** — 454 个标准化技能包，覆盖全栈开发全链路
- **智能体基础设施** — OpenClaw 插件生态、Spring AI 集成、LLM 网关
- **工程实践沉淀** — 从需求到交付的 Agent-driven 工作流

---

## 核心项目

### Agent Skills 生态

| 项目 | Stars | 说明 |
|------|-------|------|
| [full-stack-skills](https://github.com/partme-ai/full-stack-skills) | ![Stars](https://img.shields.io/github/stars/partme-ai/full-stack-skills?style=social) | 454 个 Agent Skills，42 个独立仓库 |
| [full-statck-skills](https://github.com/full-statck-skills) | — | 技能仓库组织（42 repos） |

### 智能体基础设施

| 项目 | Stars | 说明 |
|------|-------|------|
| [openclaw-plugins](https://github.com/partme-ai/openclaw-plugins) | ![Stars](https://img.shields.io/github/stars/partme-ai/openclaw-plugins?style=social) | OpenClaw 30+ 企业级插件 |
| [teams-of-agents](https://github.com/partme-ai/teams-of-agents) | ![Stars](https://img.shields.io/github/stars/partme-ai/teams-of-agents?style=social) | 多智能体协作团队 |
| [hermes-agent](https://github.com/partme-ai/hermes-agent) | — | 可成长的 AI Agent |

### Spring AI 与 LLM 工具

| 项目 | Stars | 说明 |
|------|-------|------|
| [spring-ai-examples](https://github.com/partme-ai/spring-ai-examples) | ![Stars](https://img.shields.io/github/stars/partme-ai/spring-ai-examples?style=social) | Spring AI 实践示例 |
| [spring-ai-gateway](https://github.com/partme-ai/spring-ai-gateway) | ![Stars](https://img.shields.io/github/stars/partme-ai/spring-ai-gateway?style=social) | LLM/SLM API 网关 |
| [langchain4j-examples](https://github.com/partme-ai/langchain4j-examples) | ![Stars](https://img.shields.io/github/stars/partme-ai/langchain4j-examples?style=social) | Langchain4j 实践示例 |

### AI 应用与工具

| 项目 | Stars | 说明 |
|------|-------|------|
| [agency-agents-zh](https://github.com/partme-ai/agency-agents-zh) | — | 211 个即插即用 AI 专家角色 |
| [opencli](https://github.com/partme-ai/opencli) | — | 通用 CLI Hub 与 AI 原生运行时 |
| [opencli-admin](https://github.com/partme-ai/opencli-admin) | — | 可视化内容采集/AI 打标系统 |

---

## 技术栈

```
┌─────────────────────────────────────────────────────────┐
│                    AI 智能体层                           │
│  Agent Skills · Agent Loop · 多智能体协作 · MCP 协议     │
├─────────────────────────────────────────────────────────┤
│                    模型与推理层                          │
│  LLMs · Spring AI · Langchain4j · RAG · Embeddings     │
├─────────────────────────────────────────────────────────┤
│                    工程化与交付                          │
│  DDD · 微服务 · Docker · K8s · CI/CD · 测试             │
├─────────────────────────────────────────────────────────┤
│                    前端与跨端                            │
│  Vue · React · Flutter · Tauri · uni-app · Electron     │
└─────────────────────────────────────────────────────────┘
```

---

## 快速开始

### 安装 Agent Skills

```bash
# 安装单个技能包
npx skills add full-statck-skills/tauri-skills    # 52 个 Tauri 技能
npx skills add full-statck-skills/spring-skills   # 7 个 Spring Boot 技能
npx skills add full-statck-skills/vue-skills      # 7 个 Vue.js 技能

# 手动安装
git clone https://github.com/full-statck-skills/<skill-name>.git
cp -r <skill-name>/skills/* .claude/skills/
```

### Spring AI 集成

```xml
<dependency>
    <groupId>org.springframework.ai</groupId>
    <artifactId>spring-ai-spring-boot-starter</artifactId>
</dependency>
```

---

## 贡献指南

欢迎贡献新技能或改进现有技能！

1. **Fork** 目标仓库
2. 按照 [Agent Skills 规范](https://agentskills.io/) 创建 `SKILL.md`
3. 提交 PR

技能结构规范：

```
skills/<group>-skills/<skill>/
  SKILL.md      # 技能主文档（必需）
  examples/     # 使用示例（可选）
  references/   # 参考资料（可选）
  scripts/      # 自动化脚本（可选）
```

---

## 联系我们

- Email: [partmeai@gmail.com](mailto:partmeai@gmail.com)
- GitHub: [github.com/partme-ai](https://github.com/partme-ai)
- Skills: [github.com/full-statck-skills](https://github.com/full-statck-skills)

---

<div align="center">

**学习AI · 掌握AI · 聚焦智能体驱动的应用开发与落地**

Made with ❤️ by PartMe AI Team

</div>
