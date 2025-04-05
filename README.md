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

- **Claude Desktop**  
  - **简介**：Claude 桌面版，普通人也能用。  
  - **功能**：连 Blender MCP，用自然语言建 3D 模型。  
  - **链接**：[Anthropic 官网](https://docs.anthropic.com)  
  - **截图**：
    ![Claude Desktop](https://files.mdnice.com/user/43439/8e500f0e-e4c3-453e-9439-ddc6735a6cbc.png)
  - **Tips**：不写代码也能玩，新手友好。

- **Cherry Studio**  
  - **简介**：新兴客户端，支持可视化配置。  
  - **功能**：拖拽连服务器，简单上手。  
  - **链接**：[Cherry Studio](https://github.com/CherryHQ/cherry-studio)  
  - **截图**：  
    ![Cherry Studio 配置 MCP](https://files.mdnice.com/user/43439/d3a71dcd-5ac6-4548-8200-30a793d46255.png)  
  - **Tips**：开发中，关注社区动态。

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


## AI 的超能力工具箱：MCP 服务器能帮你做什么？

简单来说，MCP 服务器就像是给 AI 安装各种“插件”或“工具”，让它不光能聊天，还能帮你干很多实实在在的活儿。下面是一些 AI 通过这些工具能获得的“超能力”：

---

### 🤖 让 AI 帮你编程、写代码、处理技术活

如果你需要 AI 帮忙写程序、检查代码或者管理技术项目，这些工具能派上用场：

| 工具名称 (Name)                                                                    | 它能帮你做什么？ (What it helps you do)                                  | 简单说 (In simple terms)                                           |
| :----------------------------------------------------------------------------- | :----------------------------------------------------------------------- | :----------------------------------------------------------------- |
| [yzfly/mcp-python-interpreter](https://github.com/yzfly/mcp-python-interpreter)  | 让 AI 帮你安全地运行 Python 代码，就像给 AI 一个专属的编程计算器。         | 让 AI 帮你写代码、算数、分析数据。                                   |
| [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai) | 在一个安全的小环境里运行 Python 代码，不用担心搞乱你的电脑。             | 安全地让 AI 运行代码片段。                                         |
| [E2B/mcp-server](https://github.com/e2b-dev/mcp-server)                        | 提供一个安全的“云端小黑屋”，让 AI 在里面放心大胆地运行代码。               | 云端的安全代码运行环境。（官方提供）                               |
| [riza-io/riza-mcp](https://github.com/riza-io/riza-mcp)                        | 让 AI 能运行各种代码，使用各种工具，更像一个真正的程序员助手。             | 强大的代码执行和工具使用平台。（官方提供）                           |
| [jamsocket/forevervm (mcp-server)](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server) | 提供一个运行 Python 代码的“沙盒”，安全隔离。                           | 另一个安全运行 Python 代码的选择。（官方提供）                       |
| [modelcontextprotocol/server-git](src/git)                                     | 让 AI 帮你管理代码版本，比如查看代码修改历史。                           | 懂代码版本管理 (Git)。                                           |
| [modelcontextprotocol/server-github](src/github)                               | 让 AI 连接到 GitHub（程序员常用的代码网站），帮你管理代码项目、查看问题。    | AI 可以帮你打理 GitHub 上的代码项目。                                |
| [oschina/mcp-gitee](https://github.com/oschina/mcp-gitee)                      | 连接到 Gitee（国内常用的代码网站），帮你管理上面的代码项目。               | AI 帮你打理 Gitee 上的项目。（Gitee 官方提供）                    |
| [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP)                  | 让 AI 分析一个代码项目里各个文件是怎么互相调用的，画出关系图。             | 帮 AI 理解复杂代码项目的结构。                                     |
| [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains)          | 让 AI 直接在你常用的编程软件 (JetBrains IDE) 里帮你写代码、改代码。        | 在你的编程工具里直接用 AI。（JetBrains 官方提供）                 |
| [semgrep/mcp](https://github.com/semgrep/mcp)                                  | 让 AI 用专业的代码检查工具 (Semgrep) 帮你找出代码里的安全隐患。          | AI 帮你检查代码安不安全。（Semgrep 官方提供）                      |
| [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP)                            | 让 AI 使用专业工具 (Ghidra) 分析软件内部是怎么工作的（逆向工程）。         | 高级技能！让 AI 分析程序内部。（适合专业人士）                         |
| [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml)                    | 让 AI 帮你管理和查看机器学习项目（MLOps）的进展。                    | 帮 AI 理解和管理机器学习流程。（ZenML 官方提供）                   |

---

### 🌐 让 AI 上网、搜索和整理信息

想让 AI 帮你浏览网页、查找资料、或者自动填写网络表格？这些工具可以：

| 工具名称 (Name)                                                                    | 它能帮你做什么？ (What it helps you do)                                      | 简单说 (In simple terms)                                               |
| :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | 让 AI 像人一样在云端打开浏览器，访问网站、点按钮、填表、抓信息。                 | AI 的“遥控浏览器”，能帮你自动操作网站。（官方提供）                        |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp)          | 微软官方工具，让 AI 像真人一样操作浏览器，自动完成网页任务，抓取数据。           | 超强网页自动化助手，微软出品。（官方提供）                               |
| [modelcontextprotocol/server-puppeteer](src/puppeteer)                         | 另一个让 AI 控制浏览器、自动访问网页、抓取信息的工具。                       | 强大的“遥控浏览器”工具。                                             |
| [modelcontextprotocol/server-fetch](src/fetch)                                 | 帮 AI 快速抓取网页内容，并整理成 AI容易理解的格式。                          | AI 的网页内容“速递员”。                                                |
| [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server)          | 提供超多 (3000+) 现成的“小机器人”(Actors)，让 AI 用它们从各种网站上抓数据。 | 海量现成的网页抓取工具库。（Apify 官方提供）                           |
| [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp)          | 让 AI 能读懂乱七八糟的网页，从中提取出整齐的结构化信息。                       | AI 的“网页信息整理师”。（AgentQL 官方提供）                            |
| [mendableai/firecrawl-mcp-server](https://github.com/mendableai/firecrawl-mcp-server) | 另一个帮 AI 从网页上抓取数据的工具。                                       | 网页数据抓取帮手。（Firecrawl 官方提供）                               |
| [screenshotone/mcp](https://github.com/screenshotone/mcp/)                     | 让 AI 帮你给网站截个图。                                                   | 网页截图工具。（ScreenshotOne 官方提供）                               |
| [oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp)                  | 专业的网页抓取服务，能处理复杂网站，把抓到的数据整理好给 AI。                  | 专业级网页抓取，搞定难搞的网站。（Oxylabs 官方提供）                     |
| [hyperbrowserai/mcp](https://github.com/hyperbrowserai/mcp)                    | 新一代的 AI 网页自动化平台，让 AI 操作浏览器更强大、更高效。                   | 高级“遥控浏览器”平台。（Hyperbrowser 官方提供）                       |
| [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp)          | 一个接口搞定搜索、网页抓取、网站地图分析等多种网络信息获取任务。               | 多功能网络信息获取工具。（Search1API 官方提供）                         |
| [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) | 提供高级的网页内容搜索、研究、文件内容提取和整理功能。                         | AI 的深度研究和文件处理助手。（Vectorize 官方提供）                      |

---

### ☁️ 让 AI 管理你的云服务 (如服务器、存储)

如果你使用 AWS、Cloudflare 等云服务，可以让 AI 帮你进行一些管理操作：

| 工具名称 (Name)                                                                          | 它能帮你做什么？ (What it helps you do)                                  | 简单说 (In simple terms)                                     |
| :----------------------------------------------------------------------------------- | :----------------------------------------------------------------------- | :----------------------------------------------------------- |
| [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | 如果你用 Cloudflare 的网络服务（比如网站加速），这个能让 AI 帮你管理设置。   | 帮你管理 Cloudflare 服务。（Cloudflare 官方提供）            |
| [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server)            | 让 AI 帮你执行一些简单的 AWS 云服务命令，管理你的云资源。                  | 基础的 AWS 管理助手。                                        |
| [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven)                    | 管理 Aiven 平台上的云服务（比如数据库、消息队列等）。                      | 帮你管理 Aiven 云服务。（Aiven 官方提供）                      |
| [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) | 让 AI 更全面地操作你的 AWS 云服务资源。                                | 更强大的 AWS 管理助手。                                      |
| [baryhuang/mcp-server-aws-resources-python](https://github.com/baryhuang/mcp-server-aws-resources-python) | 通过自动生成代码的方式，让 AI 安全地查询或修改你的 AWS 资源。              | 用代码安全地管理 AWS。                                       |
| [aws-samples/sample-mcp-server-s3](https://github.com/aws-samples/sample-mcp-server-s3) | 专门用来让 AI 帮你从 AWS S3 云存储里拿文件（比如 PDF）。                 | 帮你从 AWS S3 拿文件。                                       |
| [aarora79/aws-cost-explorer-mcp-server](https://github.com/aarora79/aws-cost-explorer-mcp-server) | 让 AI 帮你分析 AWS 云服务的账单，看看哪里花钱多了，帮你省钱。              | AI 帮你分析 AWS 账单，省钱小能手。                             |
| [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops)           | 让 AI 连接到微软的 Azure DevOps（项目管理工具），帮你查询和管理工作任务。 | 帮你管理 Azure DevOps 上的任务。                             |
| [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server)        | 如果你用 Metoro 监控 K8s（一种技术架构），这个能让 AI 帮你查看和操作。   | 管理 K8s 环境。（Metoro 官方提供）                           |

---

### 🗄️ 让 AI 帮你查询和管理数据

把 AI 连接到数据库，让它帮你查找信息、分析数据：

| 工具名称 (Name)                                                                            | 它能帮你做什么？ (What it helps you do)                                          | 简单说 (In simple terms)                                        |
| :------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------- | :-------------------------------------------------------------- |
| [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse)              | 连接到 ClickHouse 这种很快的数据库，让 AI 帮你快速查找和分析里面的海量数据。       | 快速查询海量数据。（ClickHouse 官方提供）                         |
| [modelcontextprotocol/server-postgres](src/postgres)                                 | 连接到 PostgreSQL 这种常用的数据库，让 AI 帮你查询里面的信息。                     | 查询 PostgreSQL 数据库。                                      |
| [modelcontextprotocol/server-sqlite](src/sqlite)                                     | 连接到 SQLite 这种轻便的数据库文件，让 AI 帮你查询。                             | 查询 SQLite 文件数据库。                                        |
| [modelcontextprotocol/server-redis](src/redis)                                       | 连接到 Redis 这种快速缓存数据库，让 AI 帮你存取里面的临时数据。                    | 操作 Redis 快速缓存。                                         |
| [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp)                    | 连接到 Chroma 这种专门存储“知识”的向量数据库，让 AI 能进行更智能的搜索。           | AI 的“智能知识库”接口。（Chroma 官方提供）                      |
| [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) | 连接到 GreptimeDB 这种处理时间顺序数据的数据库，让 AI 帮你分析。                   | 分析时间序列数据。（GreptimeDB 官方提供）                        |
| [aliyun/alibabacloud-hologres-mcp-server](https://github.com/aliyun/alibabacloud-hologres-mcp-server) | 连接到阿里云的 Hologres 数据库，让 AI 帮你查询分析。                           | 查询阿里云 Hologres 数据。（阿里云官方提供）                      |
| [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus)        | 连接到 Milvus 向量数据库，让 AI 能在里面进行智能搜索和查询。                       | AI 的另一个“智能知识库”接口。（Milvus 官方提供）                 |
| [motherduckdb/mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck) | 连接到 MotherDuck 或本地的 DuckDB 数据库，让 AI 帮你查询和分析数据。                 | 查询 DuckDB 数据（云端或本地）。（MotherDuck 官方提供）           |
| [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)               | 连接到 Neo4j 这种“关系图”数据库，让 AI 帮你理解和查询复杂的关系网络。                | 分析关系网络数据。（Neo4j 官方提供）                            |
| [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon)        | 连接到 Neon 提供的云端 PostgreSQL 数据库服务。                                | 查询 Neon 云数据库。（Neon 官方提供）                             |
| [oceanbase/mcp-oceanbase](https://github.com/oceanbase/mcp-oceanbase)                | 连接到 OceanBase 这种大型分布式数据库。                                        | 查询 OceanBase 数据库。（OceanBase 官方提供）                   |
| [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant/)             | 连接到 Qdrant 向量数据库，给 AI 一个“记忆层”，让它能根据意思找到相关信息。           | AI 的“语义记忆”接口。（Qdrant 官方提供）                         |
| [singlestore-labs/mcp-server-singlestore](https://github.com/singlestore-labs/mcp-server-singlestore) | 连接到 SingleStore 数据库平台。                                              | 查询 SingleStore 数据库。（SingleStore 官方提供）                |
| [StarRocks/mcp-server-starrocks](https://github.com/StarRocks/mcp-server-starrocks)    | 连接到 StarRocks 数据库。                                                    | 查询 StarRocks 数据库。（StarRocks 官方提供）                     |
| [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird)                | 连接到 Tinybird 实时数据平台（基于 ClickHouse）。                              | 查询 Tinybird 实时数据。（Tinybird 官方提供）                     |
| [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server)    | 让 AI 帮你读取和修改 Airtable（像智能表格的数据库）里的数据。                      | 操作 Airtable 表格数据。                                        |
| [felores/airtable-mcp](https://github.com/felores/airtable-mcp)                      | 另一个让 AI 操作 Airtable 的工具。                                           | 备选的 Airtable 操作工具。                                      |
| [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb)      | 连接到 ArangoDB 这种支持多种数据模型的数据库。                               | 查询 ArangoDB 数据库。                                        |
| [lishenxydlgzs/aws-athena-mcp](https://github.com/lishenxydlgzs/aws-athena-mcp)        | 让 AI 使用 AWS Athena 服务查询存储在云端的数据。                             | 让 AI 查询 AWS Athena 上的数据。                                |
| [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server)                | 连接到微软 Azure 的 Data Explorer 数据库，让 AI 查询和分析。                   | 查询 Azure Data Explorer 数据。                                 |

---

### 📄 让 AI 处理你的文件和文档 (如 Excel, PDF)

需要 AI 帮你读写 Excel、PDF 文件，或者管理云盘文件吗？

| 工具名称 (Name)                                                                  | 它能帮你做什么？ (What it helps you do)                                          | 简单说 (In simple terms)                                    |
| :--------------------------------------------------------------------------- | :------------------------------------------------------------------------------- | :---------------------------------------------------------- |
| [yzfly/mcp-excel-server](https://github.com/yzfly/mcp-excel-server)          | 让 AI 直接跟你用自然语言交流来操作 Excel 文件，比如读数据、写内容、做分析。          | AI 帮你搞定 Excel！                                       |
| [modelcontextprotocol/server-filesystem](src/filesystem)                     | 让 AI 能够安全地访问和操作你电脑上的文件。                                       | AI 可以读写本地文件。                                       |
| [modelcontextprotocol/server-gdrive](src/gdrive)                             | 让 AI 帮你搜索和访问你 Google Drive（谷歌云盘）里的文件。                        | AI 帮你管理 Google Drive 文件。                             |
| [box-community/mcp-server-box](https://github.com/box-community/mcp-server-box) | 让 AI 连接到 Box 企业云盘，帮你管理和使用里面的文件。                            | AI 帮你管理 Box 企业云盘。（Box 官方提供）                     |
| [Unstructured-IO/UNS-MCP](https://github.com/Unstructured-IO/UNS-MCP)        | 使用 Unstructured 的强大能力，让 AI 处理各种格式混乱的文件（如 PDF, Word），提取信息。 | AI 的“文件整理大师”，搞定各种乱七八糟的文件。（官方提供）        |
| [needle-ai/needle-mcp](https://github.com/needle-ai/needle-mcp)              | 让 AI 能在你上传的文档（PDF, Word 等）里进行智能搜索和问答。                     | AI 能读懂你的文档并回答问题。（Needle 官方提供）               |
| [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) | 提供一种特殊的文件存储方式，带有版本记录和实时同步。                             | 特殊的文件存储和同步。（Fireproof 官方提供）                 |
| [Verodat/verodat-mcp-server](https://github.com/Verodat/verodat-mcp-server)  | 连接到 Verodat 数据平台，让 AI 处理里面的数据。                                | 操作 Verodat 平台数据。（Verodat 官方提供）                  |

---

### 🔍 让 AI 帮你精准搜索最新信息

有时候 AI 的知识不够新，需要让它上网搜一下？这些工具可以：

| 工具名称 (Name)                                                                    | 它能帮你做什么？ (What it helps you do)                                | 简单说 (In simple terms)                                   |
| :----------------------------------------------------------------------------- | :--------------------------------------------------------------------- | :--------------------------------------------------------- |
| [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server)          | 使用 Exa 这个专为 AI 设计的搜索引擎，让 AI 获取更靠谱、更新的网页信息。    | AI 专用搜索引擎。（Exa 官方提供）                            |
| [modelcontextprotocol/server-brave-search](src/brave-search)                 | 让 AI 使用 Brave 搜索引擎来查找网页信息。                                | 使用 Brave 搜索。                                        |
| [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp)                    | 让 AI 使用 Kagi 这个付费搜索引擎，据说结果更好、无广告。                     | 使用 Kagi 高质量搜索。（Kagi 官方提供）                       |
| [ppl-ai/modelcontextprotocol](https://github.com/ppl-ai/modelcontextprotocol)  | 连接到 Perplexity，让 AI 能进行实时全网搜索，像 Perplexity AI 一样回答问题。 | 像 Perplexity AI 一样实时搜索回答。（Perplexity 官方提供）   |
| [tavily-ai/tavily-mcp](https://github.com/tavily-ai/tavily-mcp)                | 另一个专为 AI 设计的搜索引擎，能搜索并提取关键信息给 AI。                    | AI 搜索+信息提取助手。（Tavily 官方提供）                    |
| [inkeep/mcp-server-python](https://github.com/inkeep/mcp-server-python)        | 让 AI 在你指定的内容源（比如你的公司文档）里进行智能搜索。                   | 在你的专属内容里搜索。（Inkeep 官方提供）                     |
| [baidubce/app-builder](https://github.com/baidubce/app-builder)              | 让 AI 使用百度搜索。                                                   | 使用百度搜索。                                           |
| [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) | 把各种来源（邮件、聊天记录、网页）的信息喂给 AI，建立一个可搜索的知识库。      | AI 的信息聚合与搜索中心。（Graphlit 官方提供）                 |

---

### 💬 让 AI 帮你处理邮件、消息和团队任务

让 AI 成为你的沟通助理，处理邮件、Slack 消息、或者管理项目：

| 工具名称 (Name)                                                                      | 它能帮你做什么？ (What it helps you do)                                | 简单说 (In simple terms)                                       |
| :------------------------------------------------------------------------------- | :--------------------------------------------------------------------- | :------------------------------------------------------------- |
| [modelcontextprotocol/server-slack](src/slack)                                 | 让 AI 接入你的 Slack 工作群，帮你发消息、管理频道，提高团队沟通效率。        | AI 帮你用 Slack。（Slack 用户必备）                            |
| [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server)          | 让 AI 在 Dart 这个项目管理工具里帮你管理任务、文档和项目。                   | AI 帮你用 Dart 做项目管理。（Dart 官方提供）                   |
| [Fibery-inc/fibery-mcp-server](https://github.com/Fibery-inc/fibery-mcp-server)  | 让 AI 在 Fibery 这个灵活的工作空间里帮你查询信息、操作数据。                 | AI 帮你用 Fibery。（Fibery 官方提供）                          |
| [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian)            | 让 AI 连接到 Jira 和 Confluence（常用的项目管理和文档工具），帮你查信息。    | AI 帮你用 Jira 和 Confluence。                               |
| [elie222/inbox-zero (mcp-server)](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) | Inbox Zero - 一个用 AI 帮你处理邮件，实现收件箱清空的个人助手。            | AI 邮件处理助手。（Inbox Zero 官方提供）                       |
| [mailgun/mailgun-mcp-server](https://github.com/mailgun/mailgun-mcp-server)      | 让 AI 使用 Mailgun 服务帮你发送和管理邮件。                                | AI 帮你发邮件。（Mailgun 官方提供）                           |
| [gotohuman/gotohuman-mcp-server](https://github.com/gotohuman/gotohuman-mcp-server) | 当 AI 不确定怎么做或者需要授权时，可以通过这个工具把请求发给你，等你批准。 | AI 的“请示领导”按钮。（gotoHuman 官方提供）                  |

---

### 🧩 让 AI 连接和操作其他常用软件

想让 AI 帮你操作 GMail, Google Sheets, Trello, 或者几千种其他软件？

| 工具名称 (Name)                                                                            | 它能帮你做什么？ (What it helps you do)                                              | 简单说 (In simple terms)                                               |
| :------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream)                      | 连接超多 (2500+) 常用软件的 API，让 AI 能和它们互动。                                | 连接海量软件，自动化神器。                                             |
| [Zapier/mcp](https://zapier.com/mcp)                                                   | 超级强！让 AI 连接并操作超过 8000 种常用软件和服务（你能想到的几乎都有）。         | 连接 8000+ 软件！让 AI 无所不能。（Zapier 官方提供）                    |
| [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server)            | 连接到 Make (原 Integromat) 自动化平台，让 AI 触发你在 Make 里设置好的自动化流程。 | 让 AI 启动 Make 自动化流程。（Make 官方提供）                            |
| [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc)                              | 提供一种通用的方式，让 AI 跨越网络调用其他程序的功能。                             | 通用的程序间调用工具。（AgentRPC 官方提供）                             |
| [unifai-network/unifai-mcp-server](https://github.com/unifai-network/unifai-mcp-server) | 一个能让 AI 动态发现并使用各种在线工具的平台。                                     | AI 的“工具发现市场”。（UnifAI 官方提供）                               |
| [VeyraX/veyrax-mcp](https://github.com/VeyraX/veyrax-mcp)                              | 用一个工具控制超过 100 种 API 和界面组件，简化 AI 的工具使用。                     | 聚合多种 API 和界面。（VeyraX 官方提供）                               |
| [integration-app/mcp-server](https://github.com/integration-app/mcp-server)            | 专门用来让 AI 代表你的客户去操作其他的 SaaS 软件（比如 CRM, Helpdesk）。         | 帮客户连接各种 SaaS 软件。（Integration App 官方提供）                 |
| [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) | 让 AI 可以调用各种不同的聊天 AI 模型（比如 GPT, Perplexity, Groq 等）。              | 让你的 AI 能调用其他 AI。                                              |
| [apimatic/apimatic-validator-mcp](https://github.com/apimatic/apimatic-validator-mcp) | 让 AI 使用 APIMatic 工具检查 API（程序接口）的设计是否规范。                       | 帮开发者检查 API 设计。（APIMatic 官方提供）                            |

---

### 💰 让 AI 帮你分析金融数据和处理业务

需要 AI 帮你分析股票、处理支付、或者管理公司财务？

| 工具名称 (Name)                                                                        | 它能帮你做什么？ (What it helps you do)                                              | 简单说 (In simple terms)                                             |
| :--------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------- | :------------------------------------------------------------------- |
| [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp)              | 让 AI 从雅虎财经获取股票数据，帮你做一些简单的金融分析。                               | AI 帮你查股票行情。                                                |
| [financial-datasets/mcp-server](https://github.com/financial-datasets/mcp-server)  | 专为 AI 设计的股票市场数据接口，方便 AI 获取和分析金融数据。                           | AI 专用的金融数据源。（Financial Datasets 官方提供）                  |
| [bankless/onchain-mcp](https://github.com/bankless/onchain-mcp)                    | 让 AI 查询区块链上的数据，比如虚拟货币价格、交易记录等。                               | AI 帮你查链上数据。（Bankless 官方提供）                              |
| [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server)    | 提供专业的实时投资研究数据，让 AI 帮你分析市场。                                     | 专业投资研究数据。（Octagon 官方提供）                               |
| [Adfin-Engineering/mcp-server-adfin](https://github.com/Adfin-Engineering/mcp-server-adfin) | 连接到 Adfin 平台，让 AI 帮你处理收款、开发票、对账等财务工作。                        | AI 财务助手。（Adfin 官方提供）                                     |
| [AudienseCo/mcp-audiense-insights](https://github.com/AudienseCo/mcp-audiense-insights) | 让 AI 分析 Audiense 里的市场报告，告诉你目标客户是谁、他们喜欢什么。                   | AI 市场分析师。（Audiense 官方提供）                                 |
| [chargebee/agentkit (modelcontextprotocol)](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol) | 连接到 Chargebee 订阅管理平台，让 AI 帮你处理订阅相关的业务。                        | AI 帮你管客户订阅。（Chargebee 官方提供）                             |
| [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) | 让 AI 帮你起草、发送和管理电子合同。                                               | AI 合同助手。（[eSignatures.com](https://www.google.com/search?q=eSignatures.com) 官方提供）                          |
| [Fewsats/fewsats-mcp](https://github.com/Fewsats/fewsats-mcp)                      | 提供一种安全的方式，让 AI 帮你在线购买东西。                                         | AI 安全购物工具。（Fewsats 官方提供）                                |
| [ramp-public/ramp-mcp](https://github.com/ramp-public/ramp-mcp)                    | 连接到 Ramp（企业支出管理平台），让 AI 帮你分析公司花了多少钱、花在哪了。                | AI 企业消费分析师。（Ramp 官方提供）                                  |
| [stripe/agent-toolkit](https://github.com/stripe/agent-toolkit)                    | 连接到 Stripe（非常流行的在线支付平台），让 AI 帮你处理支付相关的操作。                  | AI 帮你处理在线支付。（Stripe 官方提供）                              |
| [thirdweb-dev/ai (thirdweb-mcp)](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp) | 连接到 web3 世界！让 AI 能在几千个区块链上查数据、分析合约、甚至执行交易。             | AI 的 Web3 超能力。（Thirdweb 官方提供）                              |
| [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server)              | 连接到 Xero 会计软件，让 AI 帮你查询公司的财务数据。                                 | AI 帮你查公司账本。（Xero 官方提供）                                  |
| [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp)                    | 让 AI 查询某个区块链地址（钱包地址）或域名的风险评分和资产情况。                         | AI 帮你查钱包地址风险。（BICScan 官方提供）                           |
| [calvernaz/alphavantage](https://github.com/calvernaz/alphavantage)                | 另一个获取股票市场数据的工具。                                                     | 备选的股票数据源。                                                 |
| [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp)            | 提供超多工具和资源，让 AI 能深入地与 Algorand 区块链互动。                         | 功能强大的 Algorand 区块链助手。                                     |

---

### ✨ 让 AI 掌握特殊技能 (做图、视频、地图等)

除了上面这些，还有一些工具能让 AI 掌握更特别的技能：

| 工具名称 (Name)                                                                            | 它能帮你做什么？ (What it helps you do)                                              | 简单说 (In simple terms)                                            |
| :------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------- | :------------------------------------------------------------------ |
| [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server)              | 让 AI 用一个很酷的工具 (Manim) 制作数学或科学方面的动画视频。                          | AI 帮你做科普动画。                                                 |
| [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp)      | AI 视频剪辑师！能帮你分析视频、搜索片段、甚至生成新的视频剪辑。                        | AI 帮你剪视频。                                                   |
| [modelcontextprotocol/server-google-maps](src/google-maps)                         | 让 AI 使用谷歌地图，帮你查地点、规划路线。                                           | AI 帮你用谷歌地图。                                                 |
| [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp)                                | 给 AI 一个“记忆库”，能记住你的编程习惯、常用代码片段，还能在里面搜索技术文档。            | AI 的“程序员笔记本”。（mem0 官方提供）                               |
| [modelcontextprotocol/server-memory](src/memory)                                     | 给 AI 一个更强大的“长期记忆”，用知识图谱的方式存储信息。                               | AI 的高级“记忆宫殿”。                                               |
| [modelcontextprotocol/server-sentry](src/sentry)                                     | 连接到 Sentry（错误追踪工具），让 AI 帮你查看程序出了什么错。                          | AI 帮你找程序 Bug。                                                 |
| [modelcontextprotocol/server-time](src/time)                                         | 让 AI 帮你处理时间和时区转换。                                                     | AI 帮你算时间。                                                   |
| [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp)                            | 让 AI 帮你生成漂亮的界面组件（按钮、卡片等）。                                       | AI 帮你做界面设计。（21st.dev 官方提供）                           |
| [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp)              | 使用 Chronulus AI 的预测能力，让你的 AI 助手能预测未来趋势。                           | AI 预测小能手。（Chronulus AI 官方提供）                           |
| [comet-ml/opik-mcp](https://github.com/comet-ml/opik-mcp)                              | 连接到 Opik（LLM 监控工具），让 AI 帮你分析其他 AI 的运行情况（比如用了哪些提示词）。 | AI 帮你分析其他 AI。（Comet Opik 官方提供）                          |
| [devhub/devhub-cms-mcp](https://github.com/devhub/devhub-cms-mcp)                      | 让 AI 在 DevHub 网站内容管理系统里帮你管理网站内容。                                 | AI 帮你管网站内容。（DevHub 官方提供）                               |
| [EduBase/MCP](https://github.com/EduBase/MCP)                                          | 连接到 EduBase 在线学习平台，让 AI 帮你管理课程、测验等。                            | AI 学习平台助手。（EduBase 官方提供）                               |
| [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana)                        | 连接到 Grafana（数据可视化工具），让 AI 帮你查看监控图表、分析数据。                   | AI 帮你读懂监控图表。（Grafana 官方提供）                             |
| [keboola/keboola-mcp-server](https://github.com/keboola/keboola-mcp-server)          | 连接到 Keboola 数据平台，让 AI 帮你处理复杂的数据流程。                              | AI 数据处理流程助手。（Keboola 官方提供）                             |
| [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp)                      | 连接到 Logfire（日志和追踪工具），让 AI 帮你查看程序运行的详细记录。                   | AI 帮你查程序日志。（Logfire 官方提供）                               |
| [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse)        | 连接到 Langfuse（提示词管理工具），让 AI 帮你管理、测试和优化你给 AI 的指令（提示词）。 | AI 帮你优化给 AI 的指令。（Langfuse 官方提供）                       |
| [lingodotdev/lingo.dev (mcp.md)](https://github.com/lingodotdev/lingo.dev/blob/main/mcp.md) | 使用 Lingo.dev 的翻译引擎，让你的 AI 助手能流利地说各种语言。                          | AI 变身翻译大师。（Lingo.dev 官方提供）                             |
| [meilisearch/meilisearch-mcp](https://github.com/meilisearch/meilisearch-mcp)        | 连接到 Meilisearch（快速搜索引擎），让 AI 能快速搜索你提供的数据。                     | AI 的快速内部搜索。（Meilisearch 官方提供）                         |
| [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun)      | 连接到 Raygun（错误和性能监控工具），让 AI 帮你分析应用崩溃的原因和用户体验。            | AI 帮你分析应用问题。（Raygun 官方提供）                             |
| [rember/rember-mcp](https://github.com/rember/rember-mcp)                          | 让 AI 帮你把聊天中学到的知识点做成 Rember（记忆卡片应用）里的卡片，方便你复习。      | AI 帮你做记忆卡片。（Rember 官方提供）                               |
| [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) | 让 AI 控制 Ableton Live 这款专业的音乐制作软件。                                   | AI 帮你玩音乐制作。                                                 |
| [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb)    | 让 AI 帮你搜索 Airbnb（爱彼迎）上的房源信息。                                      | AI 帮你搜民宿。                                                   |
| [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) | 连接到 Airflow（任务调度工具），让 AI 帮你管理和查看定时运行的任务。                 | AI 帮你管定时任务。                                                 |
| [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server)            | 让 AI 帮你管理 Anki（记忆卡片软件）里的卡片。                                      | AI 帮你用 Anki 记东西。                                             |
| [Omar-v2/mcp-ical](https://github.com/Omar-v2/mcp-ical)                            | 让 AI 帮你查看和管理你苹果电脑上的日历事件。                                       | AI 帮你管苹果日历。                                                 |
| [vishalmysore/choturobo](https://github.com/vishalmysore/choturobo)                  | 让 AI 控制连接到 Arduino（一种微控制器板）的机器人或其他硬件。                       | AI 帮你控制机器人或硬件。（适合 DIY 爱好者）                          |

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