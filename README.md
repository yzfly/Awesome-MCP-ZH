# Awesome-MCP-ZH

![](https://files.mdnice.com/user/43439/48b72eef-4bca-4d2b-86e3-0055a1036ea7.jpg)

欢迎来到 `Awesome-MCP-ZH`，一个专为中文用户打造的 MCP（模型上下文协议）资源合集！
这里有 MCP 的基础介绍、玩法、客户端、服务器和社区资源，帮你快速上手这个 AI 界的“万能插头”。

[![简体中文](https://img.shields.io/badge/中文文档-点击查看-orange)](README.md) [![English](https://img.shields.io/badge/English-Click-yellow)](README.md)

- 作者：云中江树 （微信公众号：云中江树）

- 如果国内的朋友想免费快速的体验MCP能力，推荐 Cherry Studio（客户端） + 阿里 Qwen (大模型）的组合，优势是免费、操作简单、LLM无需魔法、无需充值。

- LLM 选型我的使用体感是： Claude3.7 > Qwen2.5-Max > DeepSeek

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

- **Claude Desktop**  
  - **简介**：Claude 桌面版，普通人也能用。  
  - **功能**：官方客户端，连接各种MCP服务器，例如连 Blender MCP，用自然语言建 3D 模型。  
  - **链接**：[Anthropic 官网](https://docs.anthropic.com)  
  - **截图**：
    ![Claude Desktop](https://files.mdnice.com/user/43439/8e500f0e-e4c3-453e-9439-ddc6735a6cbc.png)
  - **Tips**：不写代码也能玩，新手友好。

- **Cherry Studio**  
  - **简介**：新兴客户端，支持可视化配置。  
  - **功能**：点选即可配置MCP服务器，简单上手。  
  - **链接**：[Cherry Studio](https://github.com/CherryHQ/cherry-studio)  
  - **截图**：  
    ![Cherry Studio 配置 MCP](https://files.mdnice.com/user/43439/d3a71dcd-5ac6-4548-8200-30a793d46255.png)  
  - **Tips**：开发中，关注社区动态。

- **5ire**  
  - **简介**：一款现代化的 AI 助手和 MCP 客户端，支持多种主流服务提供商。  
  - **功能**：通过 MCP 协议连接工具与数据源，提供文件系统访问、数据库交互、远程数据获取等功能；支持本地知识库、使用分析、提示库、书签、快速搜索等特性。  
  - **链接**：[5ire 官网](https://5ire.app/) | [GitHub 仓库](https://github.com/nanbingxyz/5ire)  
  - **截图**：  
    ![5ire](https://files.mdnice.com/user/43439/0c1c47ad-689d-4302-824e-9dd5e2706e2c.png)
  - **Tips**：适合开发者与非开发者使用，支持多平台（Windows、macOS、Linux）。

- **Cursor**  
  - **简介**：代码编辑器，装上 MCP 变“全能选手”。  
  - **功能**：写代码、发 Slack、生成图片。  
  - **链接**：[官网](https://cursor.sh/)  
  - **截图**：
    ![Cursor](https://files.mdnice.com/user/43439/3971db3e-2a0d-4128-b6e5-bcc487034d47.png)
  - **Tips**：程序员必备，试试连 GitHub MCP。

- **DeepChat**  
  - **简介**：连接强大 AI 与个人世界的智能助手。  
  - **功能**：支持多模型云服务（如 DeepSeek、OpenAI 等）和本地模型部署（如 Ollama），具备多通道聊天并发支持、完整的 Markdown 渲染、本地文件处理、MCP 支持等特性。  
  - **链接**：[DeepChat 官网](https://deepchat.thinkinai.xyz/) | [GitHub 仓库](https://github.com/ThinkInAIXYZ/deepchat)  
  - **截图**：  
    ![DeepChat](https://files.mdnice.com/user/43439/802fc73d-6fd6-46ca-9e7c-9aff38715a88.png)
  - **Tips**：适合开发者与非开发者使用，支持多种平台（Windows、macOS、Linux），可通过 MCP 快速集成到现有工作流中。  

- **ChatWise**  
  - **简介**：功能强大且注重隐私保护。  
  - **功能**：支持任意 LLM 模型（如 GPT-4、Claude、Gemini 等），具备多模态聊天（音频、PDF、图片、文本等）、网页搜索（Tavily API 或本地浏览器）、MCP 工具集成（如 Notion、Google Sheets 等）以及实时渲染 HTML/React/图表等功能。  
  - **链接**：[ChatWise 官网](https://chatwise.app/) | [文档](https://docs.chatwise.app/)  
  - **截图**：  
    ![ChatWise](https://files.mdnice.com/user/43439/306e535a-7b7b-43c5-b6ba-02c83d167485.jpg)
  - **Tips**：数据完全本地存储，适合需要高效工具的用户；通过 MCP 扩展其功能！


---

## MCP 服务器精选列表 

模型上下文协议 (MCP) 服务器是赋予 AI 模型与外部工具、数据和系统交互能力的“工具箱”。以下是按不同应用场景精选的 MCP 服务器列表，按场景和质量（官方/参考 > 常用/成熟 > 社区/特定）排序，方便中文用户查找和使用。

**说明:**

*   **名称:** 点击可跳转到对应的 GitHub 仓库。
*   **中文介绍:** 简述该服务器的主要功能和用途。
*   **备注:** 包含开发者信息（如官方、社区）、主要技术、适用平台或关键特性。

---

### 🌐 浏览器自动化与网页交互

*(让 AI 能够像人一样浏览网页、提取信息、填写表单等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 微软官方出品，使用 Playwright 让 AI 精确控制网页，自动化抓取数据。            | 官方实现，浏览器自动化强推，适合需要精细网页交互的场景。                 |
| [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | 云端浏览器自动化服务，能导航网页、提取数据、填表单等，无需本地安装。         | 官方实现，TypeScript 开发，云端浏览器操作全能手。                        |
| [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) | 官方参考实现，使用 Puppeteer 进行浏览器自动化和网页抓取。                    | 官方参考，TypeScript 开发，网页抓取和交互基础工具。                      |
| [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server) | 集成 Apify 平台 3000+ 云工具，用于网站、电商、社交媒体等数据提取。         | 官方实现，TypeScript 开发，云端数据抓取工具库。                          |
| [AgentQL](https://github.com/tinyfish-io/agentql-mcp)                | 让 AI 代理从非结构化网页中获取结构化数据。                                | 官方实现，Python 开发，网页数据结构化提取。                           |
| [Firecrawl](https://github.com/mendableai/firecrawl-mcp-server)      | 使用 Firecrawl 提取网页数据，支持 JavaScript 渲染。                     | 官方实现，TypeScript 开发，高级网页抓取。                             |
| [Oxylabs](https://github.com/oxylabs/oxylabs-mcp)                    | 使用 Oxylabs Web API 抓取网站，支持动态渲染和结构化数据提取。              | 官方实现，Python 开发，专业级网页抓取。                               |
| [Hyperbrowser](https://github.com/hyperbrowserai/mcp)                | 新一代 AI 代理浏览器自动化平台，支持大规模、无缝操作。                     | 官方实现，TypeScript 开发，大规模浏览器自动化。                       |
| [ScreenshotOne](https://github.com/screenshotone/mcp/)               | 使用 ScreenshotOne 服务渲染网站截图。                                   | 官方实现，TypeScript 开发，网页截图工具。                             |
| [modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | 官方参考实现，灵活获取网页内容（HTML/JSON/MD），并为 AI 处理优化。       | 官方参考，Python 开发，基础网页内容获取。                             |
| [RAG Web Browser](https://github.com/apify/mcp-server-rag-web-browser) | Apify 开源工具，执行网页搜索、抓取 URL 并以 Markdown 格式返回内容。       | 社区实现 (Apify)，TypeScript 开发，结合 RAG 的网页浏览。                |
| [scrapling-fetch](https://github.com/cyberchitta/scrapling-fetch-mcp) | 从有反爬虫措施的网站获取文本内容。                                       | 社区实现，Python 开发，突破反爬。                                      |
| [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp)        | 使用 Playwright 无头浏览器获取网页内容，支持 JS 渲染和智能提取。            | 社区实现，TypeScript 开发，Playwright 网页内容提取。                 |

---

### 💻 开发与代码执行

*(让 AI 能够运行代码、分析代码库、与开发工具集成等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [yzfly/mcp-python-interpreter](https://github.com/yzfly/mcp-python-interpreter) | 安全、标准化的 Python 环境，支持代码执行、环境和包管理。                 | 社区标杆，轻量级 Python 执行环境，适合开发和数据分析。                  |
| [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai) | Pydantic 出品，在安全的沙盒环境中运行 Python 代码，适合开发编程代理。        | 官方实现 (Pydantic)，Python 开发，安全代码执行。                      |
| [E2B](https://github.com/e2b-dev/mcp-server)                         | 在 E2B 提供的安全云沙盒中运行代码。                                    | 官方实现，TypeScript 开发，云端安全代码沙盒。                         |
| [JetBrains](https://github.com/JetBrains/mcp-jetbrains)              | JetBrains 官方集成，让 AI 在 JetBrains IDE 中处理代码。                  | 官方实现，Kotlin 开发，IDE 代码操作。                                 |
| [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP)        | 分析代码库依赖关系，生成图表，帮助 AI 理解项目结构。                     | 社区实现，多语言 (Py/TS/Rust)，代码结构分析。                         |
| [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp)                | 管理代码偏好和模式，支持语义搜索，方便在 IDE 中存取技术文档。              | 官方实现，Python 开发，程序员的记忆助手和偏好管理。                     |
| [code-executor](https://github.com/bazinga012/mcp_code_executor)     | 允许 AI 在指定的 Conda 环境中执行 Python 代码。                         | 社区实现，Python 开发，Conda 环境代码执行。                           |
| [code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) | 创建安全的 Docker 容器环境来执行代码。                                 | 社区实现，Python 开发，Docker 沙盒代码执行。                           |
| [ForeverVM](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server) | 在代码沙盒中运行 Python 代码。                                          | 官方实现 (Jamsocket)，JavaScript 开发，代码沙盒。                   |
| [Riza](https://github.com/riza-io/riza-mcp)                          | Riza 提供的任意代码执行和工具使用平台。                                 | 官方实现，Go 开发，通用代码执行平台。                                |
| [Semgrep](https://github.com/semgrep/mcp)                            | 让 AI 代理使用 Semgrep 进行代码安全扫描。                               | 官方实现，Python 开发，代码安全扫描。                                |
| [ZenML](https://github.com/zenml-io/mcp-zenml)                       | 与 ZenML MLOps/LLMOps 平台交互，管理机器学习流程。                      | 官方实现，Python 开发，MLOps 流程管理。                               |
| [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc)    | 使用 Pandoc 进行无缝文档格式转换（Markdown, HTML, PDF, DOCX等）。        | 社区实现，Python 开发，文档格式转换。                                |
| [iTerm MCP](https://github.com/ferrislucas/iterm-mcp)                | 集成 macOS 的 iTerm2 终端，让 AI 执行和监控终端命令。                   | 社区实现，Python 开发，macOS 终端控制。                              |
| [Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)        | 在 Windows 系统上安全执行命令行（PowerShell, CMD, Git Bash）。          | 社区实现，Python 开发，Windows 命令行控制。                          |

---

### 🔄 版本控制 (Git / GitHub / GitLab)

*(让 AI 能够操作代码仓库、管理 Pull Request、处理 Issues 等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers) | 官方参考实现，集成 GitHub API，管理仓库、文件、PR 和 Issues。           | 官方参考，TypeScript 开发，GitHub 重度用户必备。                      |
| [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | 官方参考实现，直接操作本地 Git 仓库，进行读取、搜索和分析。              | 官方参考，Python 开发，本地 Git 仓库操作。                            |
| [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) | 官方参考实现，集成 GitLab API，进行项目管理和 CI/CD 操作。              | 官方参考，TypeScript 开发，GitLab 用户适用。                         |
| [Gitee](https://github.com/oschina/mcp-gitee)                        | Gitee 官方集成，管理 Gitee 仓库、Issues 和 Pull Requests。              | 官方实现，Go 开发，Gitee 用户必备。                                  |
| [Github Actions](https://github.com/ko1ynnky/github-actions-mcp-server) | 与 Github Actions 交互，管理工作流。                                   | 社区实现，TypeScript 开发，GitHub Actions 管理。                    |

---

### 🗄️ 数据库交互

*(让 AI 能够查询数据库、检查表结构、甚至修改数据)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) | ClickHouse 官方集成，连接 ClickHouse 数据库进行查询和模式检查。          | 官方实现，Python 开发，ClickHouse 数据分析利器。                     |
| [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers) | 官方参考实现，集成 PostgreSQL，支持查询和模式分析。                     | 官方参考，TypeScript 开发，PostgreSQL 数据库操作。                   |
| [Chroma](https://github.com/chroma-core/chroma-mcp)                  | Chroma 官方集成，用于嵌入、向量搜索、文档存储和全文搜索。                  | 官方实现，Python 开发，AI 应用数据库，向量搜索。                      |
| [Aiven](https://github.com/Aiven-Open/mcp-aiven)                     | Aiven 官方集成，导航 Aiven 项目，与 PostgreSQL®, Kafka®, ClickHouse®, OpenSearch® 服务交互。 | 官方实现，Python 开发，Aiven 云数据库管理。                          |
| [Milvus](https://github.com/zilliztech/mcp-server-milvus)            | Zilliz/Milvus 官方集成，搜索、查询和交互 Milvus 向量数据库中的数据。       | 官方实现，Python 开发，Milvus 向量数据库操作。                        |
| [MotherDuck](https://github.com/motherduckdb/mcp-server-motherduck)  | MotherDuck 官方集成，使用 MotherDuck 和本地 DuckDB 查询和分析数据。        | 官方实现，Python 开发，DuckDB 云服务交互。                           |
| [Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)                 | Neo4j 官方贡献，操作 Neo4j 图数据库（模式+读写 Cypher），并提供图数据库支持的记忆功能。 | 官方贡献，Python 开发，图数据库操作和记忆。                         |
| [Neon](https://github.com/neondatabase/mcp-server-neon)              | Neon 官方集成，与 Neon 无服务器 Postgres 平台交互。                     | 官方实现，TypeScript 开发，Neon Serverless PG 管理。               |
| [Qdrant](https://github.com/qdrant/mcp-server-qdrant/)               | Qdrant 官方集成，基于 Qdrant 向量搜索引擎实现语义记忆层。                | 官方实现，Python 开发，Qdrant 向量搜索与记忆。                      |
| [SingleStore](https://github.com/singlestore-labs/mcp-server-singlestore) | SingleStore 官方集成，与 SingleStore 数据库平台交互。                  | 官方实现，Python 开发，SingleStore 数据库操作。                     |
| [StarRocks](https://github.com/StarRocks/mcp-server-starrocks)       | StarRocks 官方集成，与 StarRocks 数据库交互。                           | 官方实现，Python 开发，StarRocks 数据仓库交互。                      |
| [Tinybird](https://github.com/tinybirdco/mcp-tinybird)               | Tinybird 官方集成，与 Tinybird 无服务器 ClickHouse 平台交互。            | 官方实现，Python 开发，Tinybird 平台交互。                          |
| [modelcontextprotocol/server-redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis) | 官方参考实现，与 Redis 键值存储进行交互。                               | 官方参考，TypeScript 开发，Redis 缓存/存储操作。                    |
| [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) | 官方参考实现，操作 SQLite 数据库，并内置商业智能能力。                   | 官方参考，Python 开发，本地 SQLite 数据库操作。                     |
| [BigQuery (by LucasHild)](https://github.com/LucasHild/mcp-server-bigquery) | 让 AI 检查 BigQuery 数据库模式并执行查询。                             | 社区实现，Python 开发，Google BigQuery 查询。                        |
| [MySQL (by designcomputer)](https://github.com/designcomputer/mysql_mcp_server) | Python 实现的 MySQL 集成，带访问控制和模式检查。                         | 社区实现，Python 开发，MySQL 数据库操作。                            |
| [MongoDB Lens](https://github.com/furey/mongodb-lens)                | 功能齐全的 MongoDB 数据库 MCP 服务器。                                   | 社区实现，TypeScript 开发，MongoDB 高级操作。                      |
| [DBHub](https://github.com/bytebase/dbhub/)                          | 通用数据库 MCP 服务器，可连接 MySQL, PostgreSQL, SQLite, DuckDB 等。    | 社区实现 (Bytebase)，TypeScript 开发，多种数据库支持。              |

---

### ☁️ 云平台与服务集成 (AWS, Cloudflare, etc.)

*(让 AI 能够管理云资源、调用云服务 API 等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)    | Cloudflare 官方集成，部署、配置和查询 Cloudflare 开发者平台资源 (Workers/KV/R2/D1)。 | 官方实现，TypeScript 开发，Cloudflare 平台管理。                   |
| [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) | 轻量级服务器，让 AI 执行 AWS CLI 命令，支持 Docker 安全运行。            | 社区实现，Python 开发，通过 CLI 管理 AWS。                           |
| [AWS KB Retrieval](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) | 官方参考实现，使用 Bedrock Agent Runtime 从 AWS 知识库检索信息。         | 官方参考，TypeScript 开发，AWS Bedrock 知识库。                   |
| [AWS Resources Operations](https://github.com/baryhuang/mcp-server-aws-resources-python) | 运行生成的 Python 代码以安全地查询或修改任何 boto3 支持的 AWS 资源。    | 社区实现，Python 开发，通过 Boto3 管理 AWS 资源。                    |
| [AWS S3](https://github.com/aws-samples/sample-mcp-server-s3)        | AWS 官方示例，灵活地从 S3 获取对象（如 PDF 文档）。                      | 官方示例 (AWS)，TypeScript 开发，S3 文件获取。                       |
| [Pulumi](https://github.com/dogukanakkaya/pulumi-mcp-server)         | 与 Pulumi API 交互，创建和列出 Stacks（基础设施即代码）。                 | 社区实现，Go 开发，Pulumi IaC 管理。                                 |
| [Kubernetes (Go)](https://github.com/strowk/mcp-k8s-go)               | Go 语言实现的 Kubernetes 服务器，用于浏览 Pods、日志、事件、命名空间等。    | 社区实现，Go 开发，Kubernetes 集群管理。                             |
| [Kubernetes and OpenShift](https://github.com/manusa/kubernetes-mcp-server) | 功能强大的 Kubernetes MCP 服务器，额外支持 OpenShift。提供 CRUD 操作及专用工具。 | 社区实现，Go 开发，Kubernetes/OpenShift 高级管理。                 |
| [VolcEngine TOS](https://github.com/dinghuazhou/sample-mcp-server-tos) | 火山引擎官方示例，灵活地从火山引擎对象存储 (TOS) 获取对象。                | 官方示例 (VolcEngine)，TypeScript 开发，火山引擎 TOS 文件获取。         |

---

### 🔍 搜索

*(让 AI 能够调用各种搜索引擎或专业搜索服务)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [Exa](https://github.com/exa-labs/exa-mcp-server)                    | Exa 官方集成，使用专为 AI 设计的 Exa 搜索引擎进行搜索。                  | 官方实现，TypeScript 开发，AI 专用搜索引擎。                          |
| [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) | 官方参考实现，使用 Brave 的搜索 API 进行网页和本地搜索。                 | 官方参考，TypeScript 开发，Brave 搜索引擎。                         |
| [Tavily](https://github.com/tavily-ai/tavily-mcp)                    | Tavily 官方集成，专为 AI 代理设计的搜索引擎（搜索+提取）。                 | 官方实现，Python 开发，AI 代理专用搜索引擎。                         |
| [Perplexity](https://github.com/ppl-ai/modelcontextprotocol)         | Perplexity 官方集成，连接 Perplexity Sonar API，实现实时全网研究。         | 官方实现，Python 开发，Perplexity 实时搜索。                        |
| [Kagi Search](https://github.com/kagisearch/kagimcp)                 | Kagi 官方集成，使用 Kagi 的搜索 API 进行网页搜索。                       | 官方实现，Python 开发，Kagi 搜索引擎。                               |
| [Search1API](https://github.com/fatwang2/search1api-mcp)             | Search1API 官方集成，一个 API 实现搜索、抓取和站点地图功能。               | 官方实现，TypeScript 开发，多功能搜索 API。                         |
| [Google Custom Search](https://github.com/adenot/mcp-google-search)  | 通过 Google 自定义搜索 API 提供 Google 搜索结果。                        | 社区实现，TypeScript 开发，Google 自定义搜索。                      |
| [Bing Web Search API](https://github.com/leehanchung/bing-search-mcp) | 微软必应网页搜索 API 的服务器实现。                                     | 社区实现，Python 开发，Bing 搜索。                                   |
| [SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng)              | 连接到 SearXNG 元搜索引擎实例。                                        | 社区实现，TypeScript 开发，SearXNG 元搜索。                       |
| [mcp-local-rag](https://github.com/nkapila6/mcp-local-rag)           | 本地运行的 RAG 式网页搜索，使用 MediaPipe Embedder 和 DuckDuckGo。       | 社区实现，Python 开发，本地 RAG 搜索 (无需 API Key)。                 |

---

### 💬 通讯与协作 (Slack, Email, etc.)

*(让 AI 能够收发消息、管理日程、参与团队协作等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers) | 官方参考实现，集成 Slack，AI 能管理频道、发消息。                       | 官方参考，TypeScript 开发，Slack 团队协作。                         |
| [Inbox Zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) | Inbox Zero 官方集成，AI 个人邮件助手。                                 | 官方实现，Python 开发，智能邮件管理。                                |
| [gotoHuman](https://github.com/gotohuman/gotohuman-mcp-server)       | gotoHuman 官方集成，允许 AI 代理和自动化向人类发送请求以供批准。         | 官方实现，TypeScript 开发，人机协作审批。                           |
| [ClaudePost](https://github.com/ZilongXue/claude-post)               | 实现 Gmail 的无缝邮件管理，支持邮件搜索、阅读和发送。                    | 社区实现，Python 开发，Gmail 邮件操作。                              |
| [Gmail](https://github.com/GongRzhe/Gmail-MCP-Server)                | 支持自动认证的 Gmail 集成，用于 Claude Desktop。                       | 社区实现，Python 开发，Gmail 集成 (带认证)。                       |
| [Gmail Headless](https://github.com/baryhuang/mcp-headless-gmail)    | 可远程托管的 Gmail 服务器，无需本地凭证或文件系统即可收发邮件。            | 社区实现，Python 开发，远程 Gmail 操作。                             |
| [Google Calendar (by v-3)](https://github.com/v-3/google-calendar)   | 集成 Google Calendar，检查日程、查找空闲时间、添加/删除事件。            | 社区实现，TypeScript 开发，Google 日历管理。                        |
| [Apple Calendar](https://github.com/Omar-v2/mcp-ical)                | 与 macOS 日历交互，创建/修改事件、列出日程、查找空闲时段等。             | 社区实现，Python 开发，macOS 日历管理。                              |
| [Discord (by v-3)](https://github.com/v-3/discordmcp)                | 通过机器人连接 Discord 服务器，读写频道消息。                            | 社区实现，TypeScript 开发，Discord 消息交互。                      |
| [Telegram](https://github.com/chigwell/telegram-mcp)                 | 通过 Telethon 集成 Telegram，支持分页读取聊天、检索和发送消息。          | 社区实现，Python 开发，Telegram 消息交互。                         |
| [LINE](https://github.com/amornpan/py-mcp-line)                      | 集成 LINE Bot，让 AI 读取和分析 LINE 对话。                            | 社区实现，Python 开发，LINE 对话分析。                               |
| [X (Twitter) (by vidhupv)](https://github.com/vidhupv/x-mcp)         | 直接通过 Claude 创建、管理和发布 X/Twitter 推文。                      | 社区实现，Python 开发，Twitter 发推管理。                            |

---

### 💰 金融与加密货币

*(让 AI 能够获取金融数据、分析股票、与区块链交互等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [Stripe](https://github.com/stripe/agent-toolkit)                    | Stripe 官方集成，与 Stripe API 交互，处理支付、客户和退款。              | 官方实现，TypeScript 开发，Stripe 支付处理。                        |
| [Chargebee](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol) | Chargebee 官方集成，将 AI 代理连接到 Chargebee 计费平台。                 | 官方实现，TypeScript 开发，Chargebee 计费管理。                     |
| [Financial Datasets](https://github.com/financial-datasets/mcp-server) | 专为 AI 代理设计的股票市场 API。                                       | 官方实现，Python 开发，AI 友好型股票数据。                          |
| [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) | 使用 Yahoo Finance API 获取金融数据，方便进行股票分析。                  | 社区实现，Python 开发，Yahoo Finance 数据获取。                      |
| [AlphaVantage](https://github.com/calvernaz/alphavantage)            | AlphaVantage 股票市场数据 API 服务器。                                 | 社区实现，Python 开发，AlphaVantage 金融数据。                     |
| [Thirdweb](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp) | Thirdweb 官方集成，读写 2000+ 区块链，查询数据、分析/部署合约、执行交易。 | 官方实现，Python 开发，多链区块链交互。                             |
| [BICScan](https://github.com/ahnlabio/bicscan-mcp)                   | 获取 EVM 区块链地址（EOA, CA, ENS）甚至域名的风险评分/资产持有情况。     | 官方实现，Python 开发，区块链地址风险分析。                         |
| [Bankless Onchain](https://github.com/bankless/onchain-mcp)          | 查询链上数据，如 ERC20 代币、交易历史、智能合约状态。                    | 官方实现，TypeScript 开发，链上数据查询。                           |
| [EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server)     | 为 30+ EVM 网络提供全面的区块链服务，支持代币、NFT、智能合约、交易和 ENS。 | 社区实现，TypeScript 开发，EVM 多链服务。                          |
| [Bsc-mcp](https://github.com/TermiX-official/bsc-mcp)                | 连接 AI 与 BNB Chain，执行复杂的链上操作（转账、交易、安全检查等）。      | 社区实现，Python 开发，BNB Chain 操作。                              |
| [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) | 使用 Solana Agent Kit 与 Solana 区块链交互，支持 40+ 协议操作。         | 社区实现，TypeScript 开发，Solana 链交互。                         |

---

### 📁 文件系统与存储

*(让 AI 能够访问本地文件、操作云存储等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers) | 官方参考实现，提供对本地文件系统的直接访问，带可配置权限。                 | 官方参考，TypeScript 开发，本地文件系统操作。                       |
| [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) | 官方参考实现，集成 Google Drive，用于列出、读取和搜索文件。             | 官方参考，TypeScript 开发，Google Drive 文件管理。                  |
| [Box](https://github.com/box-community/mcp-server-box)               | Box 官方集成，通过 Box AI 与智能内容管理平台交互。                       | 官方实现，Python 开发，Box 云存储交互。                              |
| [Fireproof](https://github.com/fireproof-storage/mcp-database-server) | Fireproof 官方集成，不可变账本数据库，支持实时同步。                     | 官方实现，TypeScript 开发，分布式数据库同步。                       |
| [Golang Filesystem Server](https://github.com/mark3labs/mcp-filesystem-server) | Go 语言实现的安全文件操作，带可配置访问控制。                            | 社区实现，Go 开发，本地文件系统操作 (Go)。                          |
| [Everything Search](https://github.com/mamertofabian/mcp-everything-search) | 在 Windows/macOS/Linux 上快速搜索文件（使用 Everything/mdfind/locate）。 | 社区实现，Python 开发，跨平台快速文件搜索。                         |
| [Obsidian Markdown Notes](https://github.com/calclavia/mcp-obsidian) | 读取和搜索 Obsidian 库或任何包含 Markdown 笔记的目录。                 | 社区实现，TypeScript 开发，Obsidian/Markdown 文件访问。             |

---

### 📊 数据分析、处理与可视化

*(让 AI 能够处理表格数据、生成图表、进行数据探索等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [yzfly/mcp-excel-server](https://github.com/yzfly/mcp-excel-server) | 通过自然语言与 Excel 交互的 MCP 服务器。                                 | 社区标杆，Excel 读写、分析、可视化。                               |
| [GreptimeDB](https://github.com/GreptimeTeam/greptimedb-mcp-server)  | GreptimeDB 官方集成，让 AI 安全地探索和分析 GreptimeDB 中的时序数据。     | 官方实现，Python 开发，GreptimeDB 时序数据分析。                    |
| [Axiom](https://github.com/axiomhq/mcp-server-axiom)                 | Axiom 官方集成，用自然语言查询和分析 Axiom 日志、追踪等事件数据。          | 官方实现，Python 开发，Axiom 日志分析。                             |
| [Comet Opik](https://github.com/comet-ml/opik-mcp)                   | Comet 官方集成，用自然语言查询和分析 Opik 日志、追踪、提示等 LLM 遥测数据。 | 官方实现，TypeScript 开发，LLM 可观测性数据分析。                     |
| [Keboola](https://github.com/keboola/keboola-mcp-server)             | Keboola 官方集成，在单一平台上构建数据工作流、集成和分析。                 | 官方实现，Python 开发，Keboola 数据平台。                           |
| [Excel (by haris-musa)](https://github.com/haris-musa/excel-mcp-server) | Excel 操作，包括读写、工作表管理、格式化、图表和数据透视表。           | 社区实现，Python 开发，Excel 高级操作。                             |
| [Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) | 对 .csv 数据集进行自主数据探索，轻松获得智能见解（**注意：会执行代码**）。 | 社区实现，Python 开发，CSV 数据自动探索。                           |
| [Dataset Viewer](https://github.com/privetin/dataset-viewer)         | 浏览和分析 Hugging Face 数据集，支持搜索、过滤、统计和导出。             | 社区实现，Python 开发，HuggingFace 数据集浏览。                    |
| [Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)   | 使用 Vega-Lite 格式和渲染器从获取的数据生成可视化图表。                  | 社区实现，Python 开发，数据可视化生成。                             |
| [QuickChart](https://github.com/GongRzhe/Quickchart-MCP-Server)      | 使用 QuickChart.io 生成图表。                                          | 社区实现，Python 开发，图表生成服务。                                |
| [Mindmap](https://github.com/YuChenSSR/mindmap-mcp-server)           | 从包含 Markdown 代码的输入生成思维导图。                               | 社区实现，Python 开发，思维导图生成。                                |
| [JSON](https://github.com/GongRzhe/JSON-MCP-Server)                  | JSON 处理服务器，支持 JSONPath 查询和多种操作。                        | 社区实现，Python 开发，高级 JSON 处理。                              |

---

### 🛠️ 效率工具与集成 (Office, Project Management, etc.)

*(让 AI 能够使用日历、任务管理、项目管理、笔记等工具)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream)    | Pipedream 官方集成，一站式连接 2500+ API，集成 8000+ 工具。              | 官方实现，Node.js 开发，超强 API/工具集成平台。                     |
| [Zapier](https://zapier.com/mcp)                                     | Zapier 官方集成，将 AI 代理即时连接到 8000+ 应用。                     | 官方实现，连接 Zapier 生态。                                         |
| [Make](https://github.com/integromat/make-mcp-server)                | Make 官方集成，将 Make 场景转换为 AI 助手可调用的工具。                  | 官方实现，TypeScript 开发，连接 Make 生态。                         |
| [Fibery](https://github.com/Fibery-inc/fibery-mcp-server)            | Fibery 官方集成，在 Fibery 工作区中执行查询和实体操作。                  | 官方实现，TypeScript 开发，Fibery 工作管理。                        |
| [Dart](https://github.com/its-dart/dart-mcp-server)                  | Dart 官方集成，与 AI 原生项目管理工具 Dart 中的任务、文档、项目数据交互。  | 官方实现，TypeScript 开发，Dart 项目管理。                          |
| [Airtable (by domdomegg)](https://github.com/domdomegg/airtable-mcp-server) | 读写 Airtable 数据库，带模式检查。                                      | 社区实现，TypeScript 开发，Airtable 读写。                         |
| [Notion (by v-3)](https://github.com/v-3/notion-server)              | Notion 集成，通过 Claude 搜索、读取、更新和创建页面。                    | 社区实现，TypeScript 开发，Notion 页面管理。                        |
| [Linear (by jerhadf)](https://github.com/jerhadf/linear-mcp-server)  | 与 Linear API 交互进行项目管理，包括搜索、创建和更新 Issues。          | 社区实现，TypeScript 开发，Linear 项目管理。                      |
| [Todoist](https://github.com/abhiz123/todoist-mcp-server)            | 与 Todoist 交互来管理你的任务。                                        | 社区实现，Python 开发，Todoist 任务管理。                            |
| [Home Assistant (by tevonsb)](https://github.com/tevonsb/homeassistant-mcp) | 与 Home Assistant 交互，查看和控制灯光、开关、传感器等智能家居设备。     | 社区实现，TypeScript 开发，智能家居控制。                           |
| [Google Tasks](https://github.com/zcaceres/gtasks-mcp)               | Google Tasks API 服务器。                                              | 社区实现，TypeScript 开发，Google Tasks 管理。                      |
| [Rember](https://github.com/rember/rember-mcp)                       | 在 Rember 中创建间隔重复抽认卡，记住聊天中学到的任何东西。               | 官方实现，TypeScript 开发，间隔重复记忆工具。                       |

---

###  multimedia 多媒体与内容创作

*(让 AI 能够生成动画、编辑视频、处理图像等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) | 用 Manim 生成动画，适合制作数学、科技类可视化内容。                      | 社区实现，本地运行，数学/科技动画。                                  |
| [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) | 视频编辑神器，支持添加、分析、搜索和生成视频剪辑。                      | 社区实现，Python 开发，视频内容创作。                                |
| [EverArt](https://github.com/modelcontextprotocol/servers/tree/main/src/everart) | 官方参考实现，使用多种模型进行 AI 图像生成。                           | 官方参考，TypeScript 开发，AI 图像生成。                            |
| [ElevenLabs](https://github.com/mamertofabian/elevenlabs-mcp-server) | 集成 ElevenLabs TTS API，能生成包含多种声音的完整画外音。              | 社区实现，Python 开发，文本转语音 TTS。                              |
| [Image Generation](https://github.com/GongRzhe/Image-Generation-MCP-Server) | 使用 Replicate Flux 模型提供图像生成能力。                             | 社区实现，Python 开发，AI 图像生成 (Replicate)。                    |
| [Replicate](https://github.com/deepfates/mcp-replicate)              | 在 Replicate 上搜索、运行和管理机器学习模型，处理生成的图像。            | 社区实现，TypeScript 开发，Replicate 模型调用。                     |
| [YouTube](https://github.com/ZubeidHendricks/youtube-mcp-server)     | 全面的 YouTube API 集成，用于视频管理、Shorts 创建和分析。               | 社区实现，Python 开发，YouTube 管理与分析。                         |

---

### 🧠 知识、记忆与 RAG

*(让 AI 拥有长期记忆、能够基于特定知识库回答问题等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | 官方参考实现，基于知识图谱的持久记忆系统。                               | 官方参考，TypeScript 开发，知识图谱记忆。                           |
| [Needle](https://github.com/needle-ai/needle-mcp)                    | Needle 官方集成，提供开箱即用的生产级 RAG，用于搜索和检索自有文档。       | 官方实现，TypeScript 开发，生产级 RAG。                            |
| [Inkeep](https://github.com/inkeep/mcp-server-python)                | Inkeep 官方集成，基于 Inkeep 的 RAG 搜索你的内容。                       | 官方实现，Python 开发，Inkeep RAG 搜索。                           |
| [Graphlit](https://github.com/graphlit/graphlit-mcp-server)          | Graphlit 官方集成，将各种来源（Slack, Gmail, 播客等）内容摄入可搜索的 Graphlit 项目。 | 官方实现，TypeScript 开发，多源内容 RAG。                         |
| [Basic Memory](https://github.com/basicmachines-co/basic-memory)     | 本地优先的知识管理系统，从 Markdown 文件构建语义图，实现跨对话持久记忆。   | 社区实现，TypeScript 开发，本地 Markdown 知识图谱记忆。               |
| [cognee-mcp](https://github.com/topoteretes/cognee/tree/main/cognee-mcp) | GraphRAG 记忆服务器，支持自定义摄取、数据处理和搜索。                    | 社区实现，TypeScript 开发，GraphRAG 记忆。                         |
| [Minima](https://github.com/dmayboroda/minima)                       | 用于本地文件 RAG 的 MCP 服务器。                                       | 社区实现，Python 开发，本地文件 RAG。                                |
| [Rememberizer AI](https://github.com/skydeckai/mcp-server-rememberizer) | 与 Rememberizer 数据源交互，促进增强的知识检索。                         | 社区实现，Python 开发，知识检索。                                    |

---

### 🔒 安全与分析

*(让 AI 能够进行安全扫描、二进制分析、风险评估等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP)                  | 集成 Ghidra 进行二进制分析，支持函数检查、反编译等。                     | 社区实现，Python+Java，本地运行，二进制逆向工程。                      |
| [Semgrep](https://github.com/semgrep/mcp)                            | Semgrep 官方集成，让 AI 代理使用 Semgrep 进行代码安全扫描。              | 官方实现，Python 开发，代码安全扫描。                                |
| [OpenCTI](https://github.com/Spathodea-Network/opencti-mcp)          | 与 OpenCTI 平台交互，检索威胁情报数据（报告、指标、恶意软件等）。          | 社区实现，Python 开发，威胁情报获取。                                |
| [Heurist Mesh Agent](https://github.com/heurist-network/heurist-mesh-mcp-server) | 访问 Heurist Mesh 网络中的专业 Web3 AI 代理，进行区块链分析、智能合约安全、代币度量等。 | 官方实现，Python 开发，Web3 安全与分析。                            |
| [BICScan](https://github.com/ahnlabio/bicscan-mcp)                   | 获取 EVM 区块链地址（EOA, CA, ENS）甚至域名的风险评分/资产持有情况。     | 官方实现，Python 开发，区块链地址风险分析。                         |
| [Whois MCP](https://github.com/bharathvaj-ganesan/whois-mcp)         | 对域名、IP、ASN 和 TLD 执行 whois 查询。                               | 社区实现，Python 开发，Whois 查询。                                  |

---

### 🛠️ 其他实用工具与集成

*(包括计算器、API 集成、特定平台工具等)*

| 名称                                                                 | 中文介绍                                                                 | 备注                                                                 |
| :------------------------------------------------------------------- | :----------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [AgentRPC](https://github.com/agentrpc/agentrpc)                     | AgentRPC 官方集成，跨网络边界连接任何语言的任何函数。                    | 官方实现，Go/Python/TS/Rust，跨语言函数调用。                       |
| [APIMatic MCP](https://github.com/apimatic/apimatic-validator-mcp)   | APIMatic 官方集成，使用 APIMatic 验证 OpenAPI 规范。                   | 官方实现，C# 开发，OpenAPI 规范验证。                               |
| [IBM wxflows](https://github.com/IBM/wxflows/tree/main/examples/mcp/javascript) | IBM 官方工具平台，为任何数据源构建、测试和部署工具。                     | 官方实现 (IBM)，JavaScript 开发，通用工具平台。                     |
| [Langfuse Prompt Management](https://github.com/langfuse/mcp-server-langfuse) | Langfuse 官方集成，用于协作编辑、版本控制、评估和发布提示的开源工具。     | 官方实现，TypeScript 开发，Prompt 管理。                          |
| [UnifAI](https://github.com/unifai-network/unifai-mcp-server)        | UnifAI 官方集成，使用 UnifAI 网络动态搜索和调用工具。                    | 官方实现，Go 开发，动态工具发现与调用。                             |
| [VeyraX](https://github.com/VeyraX/veyrax-mcp)                       | VeyraX 官方集成，单一工具控制 100+ API 集成和 UI 组件。                | 官方实现，Go 开发，大规模 API/UI 控制。                             |
| [Calculator](https://github.com/githejie/mcp-server-calculator)      | 使 LLM 能够使用计算器进行精确的数值计算。                                | 社区实现，Python 开发，基础计算器功能。                             |
| [Time](https://github.com/modelcontextprotocol/servers/tree/main/src/time) | 官方参考实现，提供时间和时区转换能力。                                 | 官方参考，TypeScript 开发，时间/时区工具。                          |
| [Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) | 官方参考实现，通过思考序列进行动态和反思性问题解决。                     | 官方参考，TypeScript 开发，复杂问题解决框架。                       |
| [OpenAPI AnyApi](https://github.com/baryhuang/mcp-server-any-openapi) | 使用内置语义搜索与大型 OpenAPI 文档交互，可自定义前缀。                  | 社区实现，Python 开发，大型 OpenAPI 交互。                           |
| [OpenAPI Schema](https://github.com/hannesj/mcp-openapi-schema)      | 让 LLM 在不增加上下文的情况下探索大型 OpenAPI 模式。                     | 社区实现，TypeScript 开发，大型 OpenAPI 模式探索。                  |
| [GraphQL Schema](https://github.com/hannesj/mcp-graphql-schema)      | 让 LLM 在不增加上下文的情况下探索大型 GraphQL 模式。                     | 社区实现，TypeScript 开发，大型 GraphQL 模式探索。                  |

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

- **MCP分析资料**  
  - [a16z 深度解读MCP](https://a16z.com/a-deep-dive-into-mcp-and-the-future-of-ai-tooling/)
  - [MCP 与 ANP 对比](https://github.com/agent-network-protocol/AgentNetworkProtocol/blob/main/blogs/cn/MCP%E4%B8%8EANP%E5%AF%B9%E6%AF%94%EF%BC%9A%E6%99%BA%E8%83%BD%E4%BD%93%E9%9C%80%E8%A6%81%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E9%80%9A%E4%BF%A1%E5%8D%8F%E8%AE%AE.md)  

## MCP Server 开发


### **1. 使用 LLM 构建 MCP 服务器**

我们可以用像 Claude 这样的大语言模型（LLM）来加速 MCP 开发！

如何使用 LLM 来构建自定义的模型上下文协议（MCP）服务器和客户端？以 Claude 为例，其他大模型（GPT、Gemini、Grok、Qwen、DeepSeek）都适用。

#### **准备文档资料**

在开始之前，请收集必要的文档资料，以帮助 Claude 理解 MCP：

1.  访问 [https://modelcontextprotocol.io/llms-full.txt](https://modelcontextprotocol.io/llms-full.txt) 并复制完整的文档文本。
2.  前往 [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) 或 [Python SDK](https://github.com/modelcontextprotocol/python-sdk) 的代码仓库。
3.  复制 README 文件和其他相关文档。
4.  将这些文档粘贴到你与 Claude 的对话中。

#### **描述你的服务器需求**

提供文档后，清晰地向 Claude 描述你想要构建什么样的服务器。请具体说明：

* 你的服务器将**开放哪些资源**
* 它将**提供哪些工具**
* 它应该**提供哪些提示（Prompts）**
* 它需要与**哪些外部系统交互**

例如：

```
构建一个 MCP 服务器，要求：
- 连接到我公司的 PostgreSQL 数据库
- 将表结构作为资源开放出来
- 提供运行只读 SQL 查询的工具
- 包含用于常见数据分析任务的提示（Prompts）
```

#### 2. 更多MCP编程资源

- [Model Context Protocol(MCP) 编程极速入门](http://github.com/liaokongVFX/MCP-Chinese-Getting-Started-Guide)

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