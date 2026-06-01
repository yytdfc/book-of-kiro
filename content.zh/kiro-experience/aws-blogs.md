---
title: "Kiro 技术博客"
weight: 30
bookToc: true
---

# Kiro 相关技术博客

以下收录了 AWS 官方博客中与 Kiro 相关的技术文章，按发布时间倒序排列。

---

## 基于Amazon Quick与Amazon Bedrock AgentCore打造对话式 FinOps助手

**日期**：2026-05-28 | **分类**：Artificial Intelligence

介绍如何将 AWS 账单相关 API 通过 MCP 协议封装为工具，部署到 Amazon Bedrock AgentCore Runtime，并接入 Amazon Quick Chat Agent。文中对 awslabs 的 billing-cost-management-mcp-server 做了改造，所有改造均通过 Kiro 以 Vibe Coding 的方式完成。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/based-on-amazon-quick-amazon-bedrock-agentcore/)

---

## 用 Kiro CLI 自动搭建 FluentBit 日志采集方案：两种 EKS 埋点数据落地 S3 Parquet 的实战对比

**日期**：2026-04-24 | **分类**：Artificial Intelligence

展示如何使用 Kiro CLI（AWS 推出的 AI 驱动命令行助手）配合 Amazon EKS MCP Server，通过自然语言对话，自动完成两种 FluentBit 日志采集方案的规划、搭建和验证。涵盖 Kiro CLI 的 Steering、Skills 和 MCP 集成等核心能力。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/kiro-cli-fluentbit-logging-solution-eks-s3-parquet-comparison/)

---

## 从 SDLC 到 AIDLC：CI&T 对 AI 驱动软件开发模式的探索及 Kiro 最佳实践

**日期**：2026-03-30 | **分类**：DevOps

了解 AIDLC 的演进脉络，以及如何利用前沿的 Agent 框架重塑整个研发流程的实践和经验。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/sdlc-aidlc-ci-t-ai-development-explore-kiro-best-practices/)

---

## 将 Kiro CLI 封装为 REST API：双通道架构实践

**日期**：2026-03-26 | **分类**：Artificial Intelligence

介绍将 Kiro CLI 封装为标准 REST API 的完整实现方案，重点说明双通道架构的设计决策，以及 ACP 协议通信中的关键技术细节。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/kiro-cli-rest-api-architecture-practice/)

---

## 当 Kiro 遇上 OpenClaw：AI Agent 双向协作的实践探索

**日期**：2026-03-26 | **分类**：Artificial Intelligence

探索 Kiro 与 OpenClaw 基于 MCP + ACP 双协议的双向协作架构。四个实战案例验证了该模式在架构评审、智能运维、数据日报、异步编码场景下的显著效率提升。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/kiro-openclaw-ai-agent-practice-explore/)

---

## AI 驱动的 Graviton 迁移评估：Kiro Power 实战指南

**日期**：2026-03-25 | **分类**：Business Productivity

深入探讨如何利用 Kiro Power 加速 Graviton 迁移，涵盖代码分析、依赖检查、容器适配的完整流程。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/ai-graviton-migration-kiro-power-guide/)

---

## 使用 Kiro CLI 和 Agent Client Protocol 构建飞书 AI 聊天机器人

**日期**：2026-03-24 | **分类**：Artificial Intelligence

如何将 Kiro CLI 变成通用 Agent 后端，并用不到 1000 行 Rust 代码构建一个飞书聊天机器人。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/using-kiro-cli-agent-client-protocol-build-ai-chat/)

---

## 让 Kiro 和 Claude Code 响应 IM 消息：用 ACP Bridge 打造异步 AI 编程工作流

**日期**：2026-03-17 | **分类**：How-To

介绍 ACP Bridge——一个将本地 CLI 编程助手通过 ACP 协议暴露为 HTTP 服务的桥接工具，结合 OpenClaw Gateway 和 AWS 基础设施，实现从 Discord 消息触发异步 AI 编程任务的完整闭环。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/enable-kiro-and-claude-code-for-im-with-acp-bridge-async-ai-workflow/)

---

## 用 Kiro 构建 AI：基于 AWS 基础设施快速构建企业级 Agentic AI 平台

**日期**：2026-03-04 | **分类**：Artificial Intelligence

如何用 Kiro（AI IDE）完成全流程开发，基于 Strands Agents 框架、Amazon Bedrock AgentCore 和 AWS 基础设施，在一周内构建了一个能交付实际产出的 AI Agent 平台——全程零人工编码。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/building-enterprise-agentic-ai-with-kiro-on-aws/)

---

## 把 Kiro CLI 当作 Agent SDK：一键订阅即可构建你的 Agent 应用

**日期**：2026-03-03 | **分类**：Artificial Intelligence

Kiro CLI 的 ACP 支持为 Agent 应用开发提供了一条新路径：将命令行工具转变为可编程的 Agent 后端，通过标准化协议暴露完整能力。开发者可以跳过 AI 基础设施的前期投入，专注于应用本身的业务逻辑和用户体验。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/use-kiro-cli-as-agent-sdk-build-your-agent-app-with-one-click-subscription/)

---

## 三剑合璧Quick Suite + Agent Core + Kiro联动实践：海外物流报价助手实战

**日期**：2026-01-12 | **分类**：Serverless

使用 Amazon Kiro + Amazon Bedrock AgentCore + Amazon Quick Suite 的 Serverless 架构方案，通过 Kiro 的 Spec-Driven Development 模式完成 MCP 工具代码的开发和 AgentCore 托管部署，为跨境物流业务构建智能报价助手。

🔗 [阅读全文](https://aws.amazon.com/cn/blogs/china/quick-suite-agent-core-kiro-logistics-quote-assistant/)

---

{{% hint info %}}
**持续更新**：本页面会定期收录新发布的 Kiro 相关博客。更多 AWS 官方博客请访问 [aws.amazon.com/cn/blogs/china](https://aws.amazon.com/cn/blogs/china/)。
{{% /hint %}}
