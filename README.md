# Awesome-MCP-ZH

![](https://files.mdnice.com/user/43439/48b72eef-4bca-4d2b-86e3-0055a1036ea7.jpg)

欢迎来到 `Awesome-MCP-ZH`，一个专为中文用户打造的 MCP（模型上下文协议）资源合集！
这里有 MCP 的基础介绍、玩法、客户端、服务器和社区资源，帮你快速上手这个 AI 界的“万能插头”。

[![简体中文](https://img.shields.io/badge/中文文档-点击查看-orange)](README.md) [![English](https://img.shields.io/badge/English-Click-yellow)](README.md)

- 作者：云中江树 （微信公众号：云中江树）

---

## MCP 是什么？

MCP 全称 **模型上下文协议（Model Context Protocol）**，由 Anthropic 在 2024 年 11 月推出，是个开源通信标准。简单说，它给 AI 装了个“超级网线”，让 AI 能跟外部工具、数据、系统无缝对接。

- **比喻**：AI 是个聪明但宅家的书呆子，MCP 就是它的“外卖员”，能帮它拿数据、干活儿。
- **目标**：让 AI 不只聊天，还能真动手，比如查数据库、发邮件、写代码。

![MCP 架构图](https://files.mdnice.com/user/43439/e43d85e3-53c4-440d-ad88-bd5218028b20.png)

想深入了解？看 [官方介绍](https://www.anthropic.com/news/model-context-protocol)。

---

## MCP 能干什么？

MCP 能让 AI 从“嘴炮王”变成“实干家”，以下是几个例子：

1. **连工具**：用 Slack 发消息、用 GitHub 管代码、用 Blender 建 3D 模型。
2. **查数据**：直接看你电脑文件、数据库记录，甚至网上实时信息。
3. **干复杂活儿**：写网页时，AI 能查代码、生成图片、调试页面，一条龙搞定。
4. **人机协作**：AI 干一半问你意见，你点头它再继续。

**例子**：在 Cursor 里装个 Slack MCP 服务器，AI 能一边写代码一边发消息通知团队，超省事！

---

## MCP 客户端

MCP 客户端是 AI 的“操作台”，以下是几个热门选择：

- **Cursor**  
  - **简介**：代码编辑器，装上 MCP 变“全能选手”。  
  - **功能**：写代码、发 Slack、生成图片。  
  - **链接**：[官网](https://cursor.sh/)  
  - **Tips**：程序员必备，试试连 GitHub MCP。


- **Cherry Studio**  
  - **简介**：新兴客户端，支持可视化配置。  
  - **功能**：拖拽连服务器，简单上手。  
  - **链接**：[Cherry Studio](https://github.com/CherryHQ/cherry-studio)  
  - **截图**：  
    ![Cherry Studio 配置 MCP](https://files.mdnice.com/user/43439/d3a71dcd-5ac6-4548-8200-30a793d46255.png)  
  - **Tips**：开发中，关注社区动态。

- **Claude Desktop**  
  - **简介**：Claude 桌面版，普通人也能用。  
  - **功能**：连 Blender MCP，用自然语言建 3D 模型。  
  - **链接**：[Anthropic 官网](https://docs.anthropic.com)  
  - **Tips**：不写代码也能玩，新手友好。
---

## MCP 服务器

MCP 服务器是 AI 的“工具箱”，以下是精选服务器列表：

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
|----------------------------------------------------------------------|--------------------------------------------------------------------------|----------------------------------------------------------------------|
| [yzfly/mcp-python-interpreter](https://github.com/yzfly/mcp-python-interpreter) | 安全、标准化的 Python 环境交互服务器，支持代码执行、环境管理和包管理 | 轻量级 Python 执行环境，适合开发和数据分析 |
| [yzfly/mcp-excel-server](https://github.com/yzfly/mcp-excel-server) | 通过自然语言与 Excel 交互的 MCP 服务器 | Excel 读写、分析、可视化,灵活集成 |
| [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream)    | 一站式连接 2500+ API，集成 8000+ 工具，支持云端和本地管理。              | 云+本地，功能超全，适合需要多工具集成的用户。                        |
| [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) | 用 Manim 生成动画，适合做数学、科技类可视化内容。                        | 本地运行，Windows/Linux 支持，动画爱好者必试。                       |
| [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) | 视频编辑神器，支持添加、分析、搜索和生成视频剪辑。                      | Python 开发，适合视频内容创作者。                                    |
| [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | 云端浏览器自动化，能导航网页、提取数据、填表单等。                      | 官方实现，TypeScript 开发，浏览器操作全能手。                        |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 微软官方出品，用 Playwright 让 AI 操控网页，抓取数据超方便。            | 浏览器自动化强推，适合需要网页交互的场景。                          |
| [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | 集成 Cloudflare 服务（Workers、KV、R2、D1），云端管理超简单。           | 官方实现，TypeScript 开发，云服务爱好者首选。                        |
| [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) | 轻量级服务器，让 AI 执行 AWS CLI 命令，支持 Docker 安全运行。            | Python 开发，云端管理 AWS 的利器。                                   |
| [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai) | 在安全沙盒里跑 Python 代码，适合开发编程代理。                          | 本地运行，Pydantic 出品，代码执行安全可靠。                          |
| [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers) | 集成 Slack，AI 能管理频道、发消息，团队协作更高效。                     | TypeScript 开发，Slack 用户必备。                                    |
| [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) | 连接 ClickHouse 数据库，支持查询和模式检查，数据分析超快。              | Python 开发，大数据处理的好帮手。                                    |
| [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers) | 集成 PostgreSQL，支持查询和模式分析，数据库操作一把抓。                 | TypeScript 开发，企业级数据库首选。                                  |
| [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP)        | 分析代码库依赖关系，生成图表，帮助 AI 理解项目结构。                     | Python+TypeScript+Rust，多语言支持，开发者友好。                     |
| [modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers) | 集成 GitHub API，管理仓库、PR 和问题，程序员的福音。                    | TypeScript 开发，GitHub 重度用户必试。                               |
| [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) | 用 Yahoo Finance API 获取金融数据，股票分析超方便。                     | Python 开发，金融爱好者不容错过。                                    |
| [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp)                | 管理代码偏好和模式，支持语义搜索，IDE 里存取技术文档超顺手。            | Python 开发，程序员的记忆助手。                                      |
| [modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers) | 集成 Google Maps，查位置、规划路线，地理数据一手掌握。                  | TypeScript 开发，旅行和物流场景实用。                                |
| [modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers) | 集成 Sentry.io，追踪错误和性能，开发调试更省心。                        | Python 开发，监控应用的利器。                                        |
| [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) | 用 Exa AI Search API 做网页搜索，实时信息安全获取。                     | 官方实现，TypeScript 开发，搜索功能强大。                            |
| [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP)                  | 集成 Ghidra 做二进制分析，函数检查、反编译一应俱全。                    | Python+Java，本地运行，安全分析必备。                                |

**自己写服务器**：用 Python/TypeScript，按 [MCP 文档](https://www.claudemcp.com/docs/introduction) 搭，超简单

---

## MCP 资源

想玩转 MCP？这些资源帮你省时间：

- **官方文档**  
  - [MCP 官网](https://www.claudemcp.com/)  
  - [Anthropic MCP 介绍](https://www.anthropic.com/news/model-context-protocol)  

- **开源文档**  
  - [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)
  - [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
  - [web目录](https://glama.ai/mcp/servers)。

- **社区资源**  
  - [GitHub MCP 仓库](https://github.com/anthropic/model-context-protocol)：官方代码和示例。  
  - [Reddit r/mcp](https://www.reddit.com/r/mcp/)：玩家交流，找灵感。  
  - [Discord](https://glama.ai/mcp/discord)：实时讨论，解决问题。

- **教程**  
  - [MCP 快速入门](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)  
  - [Claude Desktop 用 SQLite](https://youtu.be/wxCCzo9dGj0)  

- **中文资料**  
  - [MCP 与 ANP 对比](https://github.com/agent-network-protocol/AgentNetworkProtocol/blob/main/blogs/cn/MCP%E4%B8%8EANP%E5%AF%B9%E6%AF%94%EF%BC%9A%E6%99%BA%E8%83%BD%E4%BD%93%E9%9C%80%E8%A6%81%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E9%80%9A%E4%BF%A1%E5%8D%8F%E8%AE%AE.md)  

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yzfly/Awesome-MCP-ZH&type=Date)](https://www.star-history.com/#yzfly/Awesome-MCP-ZH&Date)

---

## 贡献指南

想加点料？欢迎贡献！  
- Fork 项目，改完提 PR。  
- 有新服务器、教程？直接加进来。  
- 详情看 [CONTRIBUTING.md](CONTRIBUTING.md)（可自己写一个）。

---

## 许可证

本项目基于 MIT 许可证，自由使用和修改，请保留版权声明。  
Copyright (c) 2025 Awesome-MCP-ZH Contributors

---