# Awesome-MCP-ZH

![](https://files.mdnice.com/user/43439/48b72eef-4bca-4d2b-86e3-0055a1036ea7.jpg)

欢迎来到 `Awesome-MCP-ZH`，一个专为中文用户打造的 MCP（模型上下文协议）资源合集！
这里有 MCP 的基础介绍、玩法、客户端、服务器和社区资源，帮你快速上手这个 AI 界的“万能插头”。

[![Join Our Discord Community](https://img.shields.io/badge/🚀%20Join%20Discord%20Community-Join%20Now-7289da?style=for-the-badge&logo=discord&logoColor=white&labelColor=2c2f33)](https://discord.gg/EXT6TpW3) [![简体中文](https://img.shields.io/badge/中文文档-点击查看-orange)](README.md) 


- 作者：云中江树 （微信公众号：云中江树）

- 如果国内的朋友想免费快速的体验MCP能力，推荐 Cherry Studio（客户端） + 阿里 Qwen (大模型）的组合，优势是免费、操作简单、LLM无需魔法、无需充值。

- LLM 选型我的使用体感是： Claude3.7 > Qwen2.5-Max > DeepSeek

分析文章：
- [ 10分钟搞定高德地图MCP！我用AI解决了约会地点选择难题 ](https://mp.weixin.qq.com/s/SUifLfJIBX_JNIZesTm8CA)
- [ 因为Manus爆火的 Claude MCP，90%人的认知可能都是错的](https://mp.weixin.qq.com/s/mT43PSiyO9ZsXKCbiVsWzQ)
- [ 刚官宣支持MCP，就发布自家Agent协议（A2A），扒一扒Google暗藏的小心思](https://mp.weixin.qq.com/s/Zoq2bgPfJIERAzPiN1l0QA)
- [阿里云拥抱 MCP 这步棋，太多人都没有真正看懂](https://mp.weixin.qq.com/s/GrEWFqpmvp1LfURAT1XzZw)
- [ 详解 MCP 传输机制 ](https://mp.weixin.qq.com/s/gmgo_glOzbvdFwePP1yQ9g)
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

- **eechat**  
  - **简介**：简单易用的本地部署 LLM 工具，注重隐私、安全和性能。  
  - **功能**：一键集成、管理、运行多种 MCP 工具，可视化配置 + 自动读取 Readme MCP 配置信息，内置 Node, Python 运行环境，兼容 Claude, Cursor 配置，同时支持本地化部署模型。
  - **链接**：[eechat 官网](https://ee.chat/) | [GitHub 仓库](https://github.com/Lucassssss/eechat)  
  - **截图**：  
    ![eechat](https://www.ee.chat/img/mcp_chat.png)
  - **Tips**：低门槛适合小白。

- **其他MCP客户端资源**  
  - [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)

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

| 名称                                                                 | 中文介绍                                                                          | 备注                                                                               |
| :------------------------------------------------------------------- | :-------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------- |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | 微软官方出品，使用 Playwright 让 AI 精确控制网页，自动化抓取数据。                   | 官方实现，浏览器自动化强推，适合需要精细网页交互的场景。                               |
| [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | 云端浏览器自动化服务，能导航网页、提取数据、填表单等，无需本地安装。                  | 官方实现 (Browserbase) 🎖️, TypeScript 开发 📇, 云端浏览器操作。                      |
| [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) | 官方参考实现，使用 Puppeteer 进行浏览器自动化和网页抓取。                           | 官方参考, TypeScript 开发 📇, 本地运行 🏠, 网页抓取和交互基础工具。                 |
| [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server) | 集成 Apify 平台 3000+ 云工具，用于网站、电商、社交媒体等数据提取。                  | 官方实现 (Apify), TypeScript 开发 📇, 云端数据抓取工具库 ☁️。                      |
| [AgentQL](https://github.com/tinyfish-io/agentql-mcp)                | 让 AI 代理从非结构化网页中获取结构化数据。                                         | 官方实现 (TinyFish IO) 🎖️, TypeScript 开发 📇, 网页数据结构化提取 ☁️。           |
| [Firecrawl](https://github.com/mendableai/firecrawl-mcp-server)      | 使用 Firecrawl 提取网页数据，支持 JavaScript 渲染。                              | 官方实现 (Mendable AI), TypeScript 开发, 高级网页抓取。                           |
| [Oxylabs](https://github.com/oxylabs/oxylabs-mcp)                    | 使用 Oxylabs Web API 抓取网站，支持动态渲染和结构化数据提取。                       | 官方实现 (Oxylabs), Python 开发, 专业级网页抓取。                                |
| [Hyperbrowser](https://github.com/hyperbrowserai/mcp)                | 新一代 AI 代理浏览器自动化平台，支持大规模、无缝操作。                              | 官方实现 (Hyperbrowser AI), TypeScript 开发, 大规模浏览器自动化。                  |
| [ScreenshotOne](https://github.com/screenshotone/mcp/)               | 使用 ScreenshotOne 服务渲染网站截图。                                            | 官方实现 (ScreenshotOne), TypeScript 开发, 网页截图工具。                          |
| [modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | 官方参考实现，灵活获取网页内容（HTML/JSON/MD），并为 AI 处理优化。                | 官方参考, Python 开发 🐍, 本地/云端 🏠☁️, 基础网页内容获取。                         |
| [automatalabs/mcp-server-playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) | 使用 Playwright 进行浏览器自动化的 MCP 服务器。                              | 社区实现, Python 开发 🐍.                                                          |
| [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) | 使用 Playwright 的 Python MCP 服务器，更适合 LLM。                         | 社区实现, Python 开发 🐍.                                                          |
| [browsermcp/mcp](https://github.com/browsermcp/mcp)                  | 自动化本地 Chrome 浏览器。                                                 | 社区实现, TypeScript 开发 📇, 本地运行 🏠.                                        |
| [co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) | 将 browser-use 打包为带 SSE 传输的 MCP 服务器，含 Dockerfile。           | 社区实现, Python 开发 🐍.                                                          |
| [executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright) | 使用 Playwright 进行浏览器自动化和网页抓取的 MCP 服务器。                    | 社区实现, TypeScript 开发 📇.                                                     |
| [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) | 与浏览器扩展配对，使 LLM 客户端能控制用户的 Firefox 浏览器。              | 社区实现, TypeScript 开发 📇, 本地运行 🏠.                                        |
| [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp)            | 从任何网站提取结构化数据，只需提示即可获得 JSON。                             | 社区实现, Python 开发 🐍, 本地运行 🏠.                                             |
| [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) | 使用 Azure OpenAI 和 Playwright 的最小化 MCP 服务器/客户端实现。           | 社区实现, Python 开发 🐍, 本地运行 🏠.                                             |
| [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) | 用于与 manifest v2 兼容浏览器交互的 MCP 服务器。                         | 社区实现, TypeScript 开发 📇, 本地运行 🏠.                                        |
| [RAG Web Browser](https://github.com/apify/mcp-server-rag-web-browser) | Apify 开源工具，执行网页搜索、抓取 URL 并以 Markdown 格式返回内容。                | 社区实现 (Apify), TypeScript 开发 📇, 结合 RAG 的网页浏览 ☁️。                    |
| [scrapling-fetch](https://github.com/cyberchitta/scrapling-fetch-mcp) | 从有反爬虫措施的网站获取文本内容。                                                | 社区实现, Python 开发, 突破反爬。                                               |
| [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp)        | 使用 Playwright 无头浏览器获取网页内容，支持 JS 渲染和智能提取 (Markdown/HTML)。 | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Playwright 网页内容提取。              |
| [ryoppippi/sitemcp](https://github.com/ryoppippi/sitemcp)           | 抓取整个网站并将其作为 MCP 服务器使用。                                          | 支持 TypeScript，提供工具命名策略、页面匹配、内容选择器等功能。可通过 NPM、Bun 等安装和运行。 |
| [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) | 支持搜索 Bilibili 内容的 MCP 服务器。                                      | 社区实现, TypeScript 开发 📇, 本地运行 🏠.                                        |

---

### 💻 开发与代码执行

*(让 AI 能够运行代码、分析代码库、与开发工具集成等)*

| 名称                                                                 | 中文介绍                                                                              | 备注                                                                                 |
| :------------------------------------------------------------------- | :------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------- |
| [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai/tree/main/mcp-run-python) | Pydantic 出品，在安全的沙盒环境中运行 Python 代码，适合开发编程代理。                   | 官方实现 (Pydantic) 🎖️, Python 开发 🐍, 本地运行 🏠, 安全代码执行。                   |
| [E2B](https://github.com/e2b-dev/mcp-server)                         | 在 E2B 提供的安全云沙盒中运行代码。                                                 | 官方实现 (E2B), TypeScript 开发, 云端安全代码沙盒。                                  |
| [JetBrains IDE Proxy](https://github.com/JetBrains/mcpProxy)           | JetBrains 官方代理，连接到 JetBrains IDE。                                       | 官方实现 (JetBrains) 🎖️, TypeScript 开发 📇, 本地运行 🏠, IDE 连接。             |
| [JetBrains](https://github.com/JetBrains/mcp-jetbrains)              | JetBrains 官方集成，让 AI 在 JetBrains IDE 中处理代码。                               | 官方实现 (JetBrains), Kotlin 开发, IDE 代码操作。                                  |
| [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js)    | 在安全可扩展的沙盒环境中执行 LLM 生成的代码，并用 JS/Python 创建自定义 MCP 工具。 | 官方实现 (YepCode) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 安全代码执行，自定义工具。       |
| [yzfly/mcp-python-interpreter](https://github.com/yzfly/mcp-python-interpreter) | 安全、标准化的 Python 环境，支持代码执行、环境和包管理。                              | 社区标杆, 轻量级 Python 执行环境, 适合开发和数据分析。                                |
| [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP)        | 分析代码库依赖关系，生成图表，帮助 AI 理解项目结构。                                  | 社区实现, 多语言 (Py 🐍/TS 📇/Rust 🦀), 代码结构分析。                               |
| [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp)                | 管理代码偏好和模式，支持语义搜索，方便在 IDE 中存取技术文档。 (Mem0 官方)             | 官方实现 (Mem0 AI) 🎖️, Python 开发 🐍, 本地运行 🏠, 程序员的记忆助手和偏好管理。       |
| [code-executor](https://github.com/bazinga012/mcp_code_executor)     | 允许 AI 在指定的 Conda 环境中执行 Python 代码。                                      | 社区实现, Python 开发, Conda 环境代码执行。                                         |
| [code-sandbox-mcp](https://github.com/Automata-Labs-team/code-sandbox-mcp) | 创建安全的 Docker 容器环境来执行代码。                                              | 社区实现, Python 开发, Docker 沙盒代码执行。                                         |
| [ForeverVM](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server) | 在代码沙盒中运行 Python 代码。                                                     | 官方实现 (Jamsocket), JavaScript 开发, 代码沙盒。                                   |
| [Riza](https://github.com/riza-io/riza-mcp)                          | Riza 提供的任意代码执行和工具使用平台。                                              | 官方实现 (Riza), Go 开发, 通用代码执行平台。                                       |
| [Semgrep](https://github.com/semgrep/mcp)                            | 让 AI 代理使用 Semgrep 进行代码安全扫描。 (Semgrep 官方)                           | 官方实现 (Semgrep) 🎖️, TypeScript 开发 📇, 代码安全扫描 ☁️. (注意: 列表有重复, 一个Py一个TS) |
| [ZenML](https://github.com/zenml-io/mcp-zenml)                       | 与 ZenML MLOps/LLMOps 平台交互，管理机器学习流程。 (ZenML 官方)                   | 官方实现 (ZenML) 🎖️, Python 开发 🐍, 本地/云端 🏠☁️, MLOps 流程管理。               |
| [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc)    | 使用 Pandoc 进行无缝文档格式转换（Markdown, HTML, PDF, DOCX, CSV 等）。            | 社区实现, Python 开发 🐍, 本地运行 🏠, 文档格式转换。                                |
| [oraios/serena](https://github.com/oraios/serena)                    | 功能齐全的编码代理，依赖于使用语言服务器的符号化代码操作。                        | 社区实现, Python 开发 🐍, 本地运行 🏠, 编码代理。                                    |
| [ezyang/codemcp](https://github.com/ezyang/codemcp)                  | 具有基本读、写和命令行工具的编码代理。                                         | 社区实现, Python 开发 🐍, 本地运行 🏠, 编码代理。                                    |
| [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | 增强的文件系统和搜索工具，以及特定于编码的命令和提示。(也含命令行功能)              | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 跨平台 🍎🪟🐧, 编码/文件/命令行工具。     |
| [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) | 基于 HF Smolagents `LocalPythonExecutor` 的安全 Python 解释器。            | 社区实现, Python 开发, 本地安全 Python 执行。                                        |
| [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor)      | 面向行的文本文件编辑器。针对 LLM 工具优化，通过高效的部分文件访问最小化 Token 使用。 | 社区实现, Python 开发 🐍, 本地运行 🏠, 文本编辑。                                     |
| [VSCode Devtools](https://github.com/biegehydra/BifrostMCP)            | 连接到 VSCode IDE 并使用语义工具，如 `find_usages`。                         | 社区实现, TypeScript 开发 📇, VSCode 集成。                                        |
| [xzq.xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server)      | 基于 JVM 的 MCP 服务器实现项目。                                            | 社区实现, TypeScript 开发 📇, 本地运行 🏠, JVM 集成。                              |
| [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe)    | 高效地向代理提供 TypeScript API 信息，使其能够处理未经训练的 API。             | 官方实现 (yWorks), TypeScript 开发 📇, 本地运行 🏠, TypeScript API 信息。           |
| [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp)            | 灵活获取 JSON、文本和 HTML 数据的 MCP 服务器。                               | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 数据获取。                                 |
| [idosal/git-mcp](https://github.com/idosal/git-mcp)                  | 通用远程 MCP 服务器，用于连接任何 GitHub 仓库或项目以获取文档。                  | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 远程 GitHub 文档访问 ([gitmcp.io](https://gitmcp.io/))。 |
| [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp)        | 用于与 Bugsnag 交互的 MCP 服务器。                                         | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Bugsnag 集成。                              |
| [jordandalton/restcsv-mcp-server](https://github.com/JordanDalton/RestCsvMcpServer) | 用于 CSV 文件的 MCP 服务器。                                               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, CSV 处理。                                 |
| [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) | 将 Jupyter Notebook 连接到 Claude AI，允许 Claude 直接交互和控制 Jupyter。 | 社区实现, Python 开发 🐍, 本地运行 🏠, Jupyter 集成。                               |

---

### 🖥️ 命令行与 Shell 交互

*(让 AI 能够执行命令行指令、与 Shell 交互)*

| 名称                                                                 | 中文介绍                                                                                        | 备注                                                                                      |
| :------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------- |
| [iTerm MCP](https://github.com/ferrislucas/iterm-mcp)                | 集成 macOS 的 iTerm2 终端，让 AI 执行和监控终端命令。                                           | 社区实现, Python 开发 🐍, 本地运行 🏠, macOS 终端控制 🍎。                              |
| [Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)        | 在 Windows 系统上安全执行命令行（PowerShell, CMD, Git Bash）。                                  | 社区实现, Python 开发 🐍, 本地运行 🏠, Windows 命令行控制 🪟。                          |
| [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) | 使用 `run_command` 和 `run_script` 工具运行任何命令。                                  | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 通用命令执行。                             |
| [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) | 具有安全执行和可自定义安全策略的命令行接口。                                             | 社区实现, Python 开发 🐍, 本地运行 🏠, 安全命令行执行。                                  |
| [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) | 用于终端的 DeepSeek 类 MCP 服务器。                                                | 社区实现, Python 开发 🐍, 本地运行 🏠, 终端交互。                                         |
| [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server)    | 实现模型上下文协议 (MCP) 的安全 Shell 命令执行服务器。                                   | 社区实现, Python 开发, 安全 Shell 执行。                                                  |
| [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | 多功能工具，可管理/执行程序，读/写/搜索/编辑代码和文本文件。(也含代码/文件功能)             | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 跨平台 🍎🪟🐧, 命令行/文件/程序管理。          |

---

### 🔄 版本控制 (Git / GitHub / GitLab)

*(让 AI 能够操作代码仓库、管理 Pull Request、处理 Issues 等)*

| 名称                                                                 | 中文介绍                                                                                        | 备注                                                                                          |
| :------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------- |
| [github/github-mcp-server](https://github.com/github/github-mcp-server) | GitHub 官方出品，让 AI 通过 API 深度集成 GitHub，实现自动化工作流等。                         | 官方实现 (GitHub), Go 开发 🏎️。功能全面，推荐 Docker 部署。                                  |
| [Gitee](https://github.com/oschina/mcp-gitee)                        | Gitee 官方集成，管理 Gitee 仓库、Issues 和 Pull Requests。                                    | 官方实现 (Gitee/oschina) 🎖️, Go 开发 🏎️, 云端/本地 ☁️🏠, Gitee 用户必备。                  |
| [gitea/gitea-mcp](https://gitea.com/gitea/gitea-mcp)                 | Gitea 官方集成，通过 MCP 与 Gitea 实例交互。                                           | 官方实现 (Gitea) 🎖️, Go 开发 🏎️, 云端/本地 ☁️🏠, 跨平台 🍎🪟🐧, Gitea 集成。          |
| [modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) | 官方参考实现，集成 GitHub API，管理仓库、文件、PR 和 Issues。                                 | 官方参考, TypeScript 开发 📇, 云服务 ☁️, GitHub 重度用户必备。                             |
| [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | 官方参考实现，直接操作本地 Git 仓库，进行读取、搜索和分析。                                   | 官方参考, Python 开发 🐍, 本地运行 🏠, 本地 Git 仓库操作。                                 |
| [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) | 官方参考实现，集成 GitLab API，进行项目管理和 CI/CD 操作。                                    | 官方参考, TypeScript 开发 📇, 云端/本地 ☁️🏠, GitLab 用户适用。                         |
| [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) | 使用 LLM 读取和分析 GitHub 仓库。                                                    | 社区实现, Python 开发 🐍, 本地运行 🏠, GitHub 仓库分析。                                  |
| [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) | 用于 GitHub Enterprise API 集成的 MCP 服务器。                                       | 社区实现, TypeScript 开发 📇, 云端/本地 ☁️🏠, GitHub Enterprise 集成。                  |
| [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) | 无缝地与 GitLab 项目的 Issues 和 Merge Requests 交互。                                | 社区实现, TypeScript 开发 📇, 云服务 ☁️, GitLab Issues/MR 操作。                       |
| [Github Actions](https://github.com/ko1ynnky/github-actions-mcp-server) | 与 Github Actions 交互，管理工作流。                                                          | 社区实现, TypeScript 开发, GitHub Actions 管理。                                          |
| [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) | 用于仓库管理、工作项和流水线的 Azure DevOps 集成。                                  | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Azure DevOps 集成。                          |

---

### 🗄️ 数据库交互

*(让 AI 能够查询数据库、检查表结构、甚至修改数据)*

| 名称                                                                 | 中文介绍                                                                                              | 备注                                                                                                       |
| :------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| [Aiven](https://github.com/Aiven-Open/mcp-aiven)                     | Aiven 官方集成，导航 Aiven 项目，与 PostgreSQL®, Kafka®, ClickHouse®, OpenSearch® 服务交互。          | 官方实现 (Aiven) 🎖️, Python 开发 🐍, 云服务 ☁️, Aiven 云数据库管理。                                       |
| [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) | ClickHouse 官方集成，连接 ClickHouse 数据库进行查询和模式检查。                                       | 官方实现 (ClickHouse) 🎖️, Python 开发 🐍, 云服务 ☁️, ClickHouse 数据分析利器。                             |
| [Chroma](https://github.com/chroma-core/chroma-mcp)                  | Chroma 官方集成，用于嵌入、向量搜索、文档存储和全文搜索。                                                 | 官方实现 (Chroma) 🎖️, Python 开发 🐍, 本地/云端 🏠☁️, AI 应用数据库，向量搜索。                           |
| [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) | Confluent 集成，与 Confluent Kafka 和 Confluent Cloud REST API 交互。                          | 官方实现 (Confluent) 🎖️, Python 开发 🐍, 云服务 ☁️, Kafka 集成。                                      |
| [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) | Fireproof 官方集成，不可变账本数据库，支持实时同步。                                                    | 官方实现 (Fireproof) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 分布式数据库同步。                            |
| [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) | Google 官方开源 MCP 服务器，专注于为数据库提供简单、快速、安全的工具。                            | 官方实现 (Google) 🎖️, Go 开发 🏎️, 云服务 ☁️, Google Cloud 数据库工具。                           |
| [GreptimeDB](https://github.com/GreptimeTeam/greptimedb-mcp-server)  | GreptimeDB 官方集成，让 AI 安全地探索和分析 GreptimeDB 中的时序数据。                                   | 官方实现 (Greptime) 🎖️, Python 开发 🐍, 本地运行 🏠, GreptimeDB 时序数据分析。                           |
| [Milvus](https://github.com/zilliztech/mcp-server-milvus)            | Zilliz/Milvus 官方集成，搜索、查询和交互 Milvus 向量数据库中的数据。                                    | 官方实现 (Zilliz/Milvus) 🎖️, Python 开发 🐍, 本地/云端 🏠☁️, Milvus 向量数据库操作。                    |
| [MotherDuck](https://github.com/motherduckdb/mcp-server-motherduck)  | MotherDuck 官方集成，使用 MotherDuck 和本地 DuckDB 查询和分析数据。                                     | 官方实现 (MotherDuck), Python 开发, DuckDB 云服务交互。                                                    |
| [Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)                 | Neo4j 官方贡献，操作 Neo4j 图数据库（模式+读写 Cypher），并提供图数据库支持的记忆功能。                     | 官方贡献 (Neo4j) 🎖️, Python 开发 🐍, 本地运行 🏠, 图数据库操作和记忆。                                  |
| [Neon](https://github.com/neondatabase/mcp-server-neon)              | Neon 官方集成，与 Neon 无服务器 Postgres 平台交互，创建和管理数据库。                                   | 官方实现 (Neon) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Neon Serverless PG 管理。                          |
| [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) | Nile 的 Postgres 平台 MCP 服务器 - 使用 LLM 管理和查询 Postgres 数据库、租户、用户、认证。     | 官方实现 (Nile) 🎖️, Python 开发, Nile PG 平台管理。                                                  |
| [Qdrant](https://github.com/qdrant/mcp-server-qdrant/)               | Qdrant 官方集成，基于 Qdrant 向量搜索引擎实现语义记忆层。                                                 | 官方实现 (Qdrant) 🎖️, Python 开发 🐍, 本地运行 🏠, Qdrant 向量搜索与记忆。                            |
| [SingleStore](https://github.com/singlestore-labs/mcp-server-singlestore) | SingleStore 官方集成，与 SingleStore 数据库平台交互。                                                 | 官方实现 (SingleStore), Python 开发, SingleStore 数据库操作。                                           |
| [StarRocks](https://github.com/StarRocks/mcp-server-starrocks)       | StarRocks 官方集成，与 StarRocks 数据库交互。                                                          | 官方实现 (StarRocks), Python 开发, StarRocks 数据仓库交互。                                            |
| [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) | Supabase 官方 MCP 服务器，将 AI 助手直接连接到你的 Supabase 项目，允许执行任务如管理表、获取配置和查询数据。 | 官方实现 (Supabase Community) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Supabase 项目管理与查询。         |
| [Tinybird](https://github.com/tinybirdco/mcp-tinybird)               | Tinybird 官方集成，与 Tinybird 无服务器 ClickHouse 平台交互 (查询和 API 能力)。                       | 官方实现 (Tinybird) 🎖️, Python 开发 🐍, 云服务 ☁️, Tinybird 平台交互。                               |
| [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) | 连接到 Weaviate 集合作为知识库，并将 Weaviate 用作聊天记忆存储的 MCP 服务器。                 | 官方实现 (Weaviate) 🎖️, Python/TypeScript 开发 🐍📇, 云服务 ☁️, Weaviate 知识库/记忆。            |
| [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) | 官方参考实现，集成 PostgreSQL，支持查询和模式分析。                                                    | 官方参考, TypeScript 开发 📇, 本地运行 🏠, PostgreSQL 数据库操作。                                  |
| [modelcontextprotocol/server-redis](https://github.com/modelcontextprotocol/servers/tree/main/src/redis) | 官方参考实现，与 Redis 键值存储进行交互。                                                              | 官方参考, TypeScript 开发, Redis 缓存/存储操作。                                                      |
| [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) | 官方参考实现，操作 SQLite 数据库，并内置商业智能能力。                                                  | 官方参考, Python 开发 🐍, 本地运行 🏠, 本地 SQLite 数据库操作。                                        |
| [DBHub](https://github.com/bytebase/dbhub/)                          | 通用数据库 MCP 服务器，可连接 MySQL, PostgreSQL, SQLite, DuckDB 等。                                  | 社区实现 (Bytebase) 🎖️, TypeScript 开发 📇, 本地运行 🏠, 多种数据库支持。                           |
| [alexanderzuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) | Supabase MCP 服务器，支持 SQL 查询执行和数据库探索工具。                                       | 社区实现, Supabase 集成。                                                                         |
| [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) | 阿里云 Tablestore MCP 服务，功能包括添加文档、基于向量和标量的文档语义搜索、RAG 友好、Serverless。 | 官方实现 (Alibaba Cloud) 🎖️, Java/Python 开发 ☕🐍, 云服务 ☁️, 阿里云 Tablestore。              |
| [benborla29/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) | NodeJS 中的 MySQL 数据库集成，具有可配置的访问控制和模式检查。                               | 社区实现, Node.js 开发, 云端/本地 ☁️🏠, MySQL 集成 (Node.js)。                                   |
| [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb)     | TiDB 数据库集成，具有模式检查和查询能力。                                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, TiDB 集成。                                               |
| [Canner/wren-engine](https://github.com/Canner/wren-engine)          | 面向 MCP 客户端和 AI Agents 的语义引擎。                                                        | 社区实现, Python/Rust 开发 🐍🦀, 本地运行 🏠, 语义引擎。                                        |
| [centralmind/gateway](https://github.com/centralmind/gateway)        | MCP 和 MCP SSE 服务器，根据数据库模式和数据自动生成 API。支持 PG, Clickhouse, MySQL, Snowflake, BigQuery, Supabase。 | 社区实现, Go 开发 🏎️, 本地运行 🏠, 跨平台 🍎🪟, 数据库 API 自动生成。                        |
| [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) | 提供 Elasticsearch 交互的 MCP 服务器实现。                                                 | 社区实现, Python 开发 🐍, 本地运行 🏠, Elasticsearch 集成。                                     |
| [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) | Trino MCP 服务器，用于从 Trino 集群查询和访问数据。                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, Trino 集成。                                               |
| [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) | Python 实现的 MySQL 集成，带访问控制和模式检查。                                                        | 社区实现, Python 开发 🐍, 本地运行 🏠, MySQL 数据库操作。                                        |
| [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) | 读写 Airtable 数据库，带模式检查。                                                                | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Airtable 读写。                                      |
| [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) | Nocodb 数据库集成，读写能力。                                                            | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Nocodb 集成。                                       |
| [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) | Google BigQuery 集成的服务器实现，支持直接访问和查询。                                       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, BigQuery 集成 (TS)。                                   |
| [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server)    | 基于 Node.js 的 MySQL 数据库集成，提供安全的数据库操作。                                    | 社区实现, Node.js 开发, 本地运行 🏠, MySQL 集成 (Node.js)。                                     |
| [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server)    | 高性能多数据库 MCP 服务器 (Go)，支持 MySQL & PG (NoSQL 即将推出)。含查询、事务、模式探索等工具。 | 社区实现, Go 开发 🏎️, 本地运行 🏠, 多数据库支持 (Go)。                                        |
| [furey/mongodb-lens](https://github.com/furey/mongodb-lens)            | 功能齐全的 MongoDB 数据库 MCP 服务器。                                                            | 社区实现, TypeScript 开发 📇, 本地运行 🏠, MongoDB 高级操作。                                    |
| [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp)        | Firebase 服务，包括 Auth、Firestore 和 Storage。                                            | 社区实现, Firebase 集成 🔥, 云服务 ☁️.                                                        |
| [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) | Convex 数据库集成，用于内省表、函数和运行一次性查询。                                         | 官方实现 (Convex) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Convex 集成。 ([Source](https://github.com/get-convex/convex-backend/blob/main/npm-packages/convex/src/cli/mcp.ts)) |
| [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) | 提供对 SQLite 数据库安全只读访问的 MCP 服务器 (FastMCP)。LLM 可探索查询，带安全特性和查询验证。 | 社区实现, Python 开发 🐍, 本地运行 🏠, SQLite 安全只读访问 (FastMCP)。                         |
| [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) | 对 InfluxDB OSS API v2 执行查询。                                                        | 社区实现, TypeScript 开发 📇, 云端/本地 ☁️🏠, InfluxDB 查询。                                  |
| [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) | Snowflake 集成，实现读和（可选）写操作以及洞察跟踪。                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, Snowflake 集成。                                        |
| [joshuarileydev/supabase-mcp-server](https://github.com/joshuarileydev/supabase) | 用于在 Supabase 中管理和创建项目及组织的 Supabase MCP 服务器。                                | 社区实现, Supabase 管理。                                                                       |
| [jovezhong/mcp-timeplus](https://github.com/jovezhong/mcp-timeplus)    | Apache Kafka 和 Timeplus 的 MCP 服务器。能列出 Kafka 主题、轮询消息、本地保存数据并通过 Timeplus 用 SQL 查询流数据。 | 社区实现, Python 开发 🐍, 云服务 ☁️, Kafka/Timeplus 集成。                                   |
| [KashiwaByte/vikingdb-mcp-server](https://github.com/KashiwaByte/vikingdb-mcp-server) | VikingDB 集成，具有集合和索引介绍、向量存储和搜索能力。                                     | 社区实现, Python 开发 🐍, 云服务 ☁️, VikingDB 集成。                                          |
| [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) | 用于 MongoDB 的模型上下文协议服务器。                                                       | 社区实现, TypeScript 开发 📇, 本地运行 🏠, MongoDB 集成 (TS)。                                |
| [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) | DuckDB 数据库集成，具有模式检查和查询能力。                                                 | 社区实现, Python 开发 🐍, 本地运行 🏠, DuckDB 集成。                                          |
| [BigQuery (by LucasHild)](https://github.com/LucasHild/mcp-server-bigquery) | 让 AI 检查 BigQuery 数据库模式并执行查询。                                                         | 社区实现, Python 开发 🐍, 云服务 ☁️, Google BigQuery 查询。                                    |
| [mcp-server-jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) | 连接到任何兼容 JDBC 的数据库，并执行查询、插入、更新、删除等操作。                           | 社区实现 (Quarkiverse), Java 开发 ☕, 本地运行 🏠, 通用 JDBC 连接。                            |
| [memgraph/mcp-memgraph](https://github.com/memgraph/mcp-memgraph)    | Memgraph MCP 服务器 - 包括对 Memgraph 执行查询和模式资源的工具。                               | 官方实现 (Memgraph) 🎖️, Python 开发 🐍, 本地运行 🏠, Memgraph 集成。                            |
| [openlink/mcp-server-odbc](https://github.com/OpenLinkSoftware/mcp-odbc-server) | 通过开放数据库连接 (ODBC) 协议实现通用数据库管理系统 (DBMS) 连接的 MCP 服务器。              | 社区实现 (OpenLink), Python 开发 🐍, 本地运行 🏠, 通用 ODBC 连接。                             |
| [openlink/mcp-server-sqlalchemy](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) | 通过 SQLAlchemy 使用 Python ODBC (pyodbc) 实现通用 DBMS 连接的 MCP 服务器。             | 社区实现 (OpenLink), Python 开发 🐍, 本地运行 🏠, 通用 SQLAlchemy 连接 (ODBC)。                 |
| [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server)      | 查询和分析 Azure Data Explorer 数据库。                                                  | 社区实现, Python 开发 🐍, 云服务 ☁️, Azure Data Explorer 查询。                               |
| [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) | 查询和分析 Prometheus 开源监控系统。                                                    | 社区实现, Python 开发 🐍, 云服务 ☁️, Prometheus 查询。                                      |
| [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp)    | MongoDB 集成，使 LLM 能够直接与数据库交互。                                                 | 社区实现, TypeScript 开发 📇, 本地运行 🏠, MongoDB 集成 (TS)。                                |
| [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) | 将 AI 工具直接连接到 Airtable。使用自然语言查询、创建、更新和删除记录。功能包括库管理、表操作等。 | 社区实现, Python 开发 🐍, 云服务 ☁️, Airtable 全功能操作 (Python)。                          |
| [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) | 通用 SQLAlchemy 数据库集成，支持 PG, MySQL, MariaDB, SQLite, Oracle, MS SQL Server 等。含模式/关系检查和大数据集分析能力。 | 社区实现, Python 开发 🐍, 本地运行 🏠, 通用 SQLAlchemy 集成。                                  |
| [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone)        | Pinecone 集成，具有向量搜索能力。                                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, Pinecone 向量搜索。                                     |
| [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp)        | 通用数据库 MCP 服务器，支持 PG, Redshift, CockroachDB, MySQL, RDS MySQL, MS SQL Server, BigQuery, Oracle DB, SQLite。 | 社区实现, Python 开发 🐍, 本地运行 🏠, 多种数据库支持 (Python)。                               |
| [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) | DolphinDB 数据库集成，具有模式检查和查询能力。                                             | 社区实现, Python 开发 🐍, 云服务 ☁️, DolphinDB 集成。                                        |
| [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) | 支持使用自然语言查询从数据库获取数据的 MCP 服务器，由 XiyanSQL 作为 text-to-SQL LLM 驱动。   | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 自然语言转 SQL 查询 (XiyanSQL)。                    |
| [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets)    | 用于与 Google Sheets 交互的模型上下文协议服务器。提供创建、读取、更新和管理电子表格的工具。        | 社区实现, Python 开发 🐍, 云服务 ☁️, Google Sheets 操作。                                    |
| [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql)              | 易于使用、零依赖的 MySQL MCP 服务器 (Go)，具有可配置的只读模式和模式检查。                  | 社区实现, Go 开发 🏎️, 本地运行 🏠, MySQL 集成 (Go)。                                         |

---

### ☁️ 云平台与服务集成 (AWS, Cloudflare, Azure, K8s, etc.)

*(让 AI 能够管理云资源、调用云服务 API 等)*

| 名称                                                                 | 中文介绍                                                                                             | 备注                                                                                                          |
| :------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------ |
| [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)    | Cloudflare 官方集成，部署、配置和查询 Cloudflare 开发者平台资源 (Workers/KV/R2/D1)。                   | 官方实现 (Cloudflare) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Cloudflare 平台管理。                           |
| [AWS KB Retrieval](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) | 官方参考实现，使用 Bedrock Agent Runtime 从 AWS 知识库检索信息。                                     | 官方参考, TypeScript 开发, AWS Bedrock 知识库。                                                             |
| [AWS S3](https://github.com/aws-samples/sample-mcp-server-s3)        | AWS 官方示例，灵活地从 S3 获取对象（如 PDF 文档）。                                                  | 官方示例 (AWS), TypeScript 开发, S3 文件获取。                                                               |
| [VolcEngine TOS](https://github.com/dinghuazhou/sample-mcp-server-tos) | 火山引擎官方示例，灵活地从火山引擎对象存储 (TOS) 获取对象。                                           | 官方示例 (VolcEngine), TypeScript 开发, 火山引擎 TOS 文件获取。                                             |
| [alexbakers/mcp-ipfs](https://github.com/alexbakers/mcp-ipfs)        | 上传和操作 IPFS 存储。                                                                        | 社区实现, TypeScript 开发 📇, 云服务 ☁️, IPFS 存储操作。                                                 |
| [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) | 轻量级服务器，让 AI 执行 AWS CLI 命令 (带 Unix 管道和模板)，支持 Docker 安全运行 (多架构)。              | 社区实现, Python 开发 🐍, 云服务 ☁️, 通过 CLI 管理 AWS (安全 Docker)。                                      |
| [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) | 轻量级服务器，让 AI 安全地执行 Kubernetes CLI 命令 (`kubectl`, `helm`, `istioctl`, `argocd`) (带 Unix 管道)，支持 Docker 安全运行 (多架构)。 | 社区实现, Python 开发 🐍, Kubernetes CLI 操作 (安全 Docker)。                                             |
| [AWS Resources Operations](https://github.com/baryhuang/mcp-server-aws-resources-python) | 运行生成的 Python 代码以安全地查询或修改任何 boto3 支持的 AWS 资源。                                | 社区实现, Python 开发, 通过 Boto3 管理 AWS 资源。                                                          |
| [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) | 基于 MCP 的 VMware ESXi/vCenter 管理服务器，提供虚拟机管理的简单 REST API 接口。                 | 社区实现, Python 开发 🐍, 云服务 ☁️, VMware ESXi/vCenter 管理。                                          |
| [flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) | Kubernetes 集群操作的 TypeScript 实现 (pods, deployments, services)。                     | 社区实现, TypeScript 开发 📇, 云端/本地 ☁️🏠, Kubernetes 操作 (TS)。                                     |
| [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) | 使用 Azure Resource Graph 大规模查询和分析 Azure 资源的 MCP 服务器，使 AI 助手能探索监控 Azure 基础设施。 | 社区实现, TypeScript 开发 📇, 云端/本地 ☁️🏠, Azure Resource Graph 查询。                               |
| [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp)      | Azure CLI 命令行包装器，允许直接与 Azure 对话。                                                | 社区实现, Azure CLI 封装。                                                                                  |
| [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp) | 提供对 Netskope Private Access 环境中所有组件的访问，包括详细设置信息和 LLM 使用示例。           | 社区实现, 云服务 ☁️, Netskope Private Access 集成。                                                       |
| [Kubernetes (Go)](https://github.com/strowk/mcp-k8s-go)               | Go 语言实现的 Kubernetes 服务器，用于浏览 Pods、日志、事件、命名空间等。                               | 社区实现, Go 开发 🏎️, 云端/本地 ☁️🏠, Kubernetes 集群管理 (Go)。                                          |
| [Kubernetes and OpenShift](https://github.com/manusa/kubernetes-mcp-server) | 功能强大的 Kubernetes MCP 服务器，额外支持 OpenShift。提供 CRUD 操作及专用工具。                       | 社区实现, Go 开发 🏎️, 本地运行 🏠, Kubernetes/OpenShift 高级管理。                                       |
| [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp)                      | Terraform MCP 服务器，允许 AI 助手管理和操作 Terraform 环境 (读配置/分析计划/应用配置/管理状态)。   | 社区实现, Rust 开发 🦀, 本地运行 🏠, Terraform 管理。                                                    |
| [Pulumi](https://github.com/dogukanakkaya/pulumi-mcp-server)         | 与 Pulumi API 交互，创建和列出 Stacks（基础设施即代码）。                                           | 社区实现, Go 开发, Pulumi IaC 管理。                                                                        |
| [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) | 用于 Kubernetes 的 MCP 服务器，使 AI 助手能通过自然语言与 K8s 集群交互。                       | 社区实现, Python 开发 🐍, 云端/本地 ☁️🏠, Kubernetes 自然语言交互。                                      |
| [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s)          | AI 驱动的 Kubernetes 资源管理工具，允许通过自然语言操作 K8s 集群中的任何资源 (原生/CRD)。         | 社区实现, Go 开发 🏎️, 云端/本地 ☁️🏠, AI 驱动 K8s 管理。                                                |
| [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) | 基于 Go 的 MCP 服务器，用于与 Nutanix Prism Central 资源交互。                              | 社区实现, Go 开发 🏎️, 本地/云端 🏠☁️, Nutanix Prism Central 交互。                                  |
| [weibaohui/k8m](https://github.com/weibaohui/k8m)                    | 提供 MCP 多集群 Kubernetes 管理和操作，带管理界面、日志记录和近 50 个内置工具 (支持标准/CRD)。   | 社区实现, Go 开发 🏎️, 云端/本地 ☁️🏠, 多集群 K8s 管理 (带 UI)。                                       |
| [weibaohui/kom](https://github.com/weibaohui/kom)                    | 提供 MCP 多集群 Kubernetes 管理和操作。可作为 SDK 集成到项目中，含近 50 个内置工具 (支持标准/CRD)。 | 社区实现, Go 开发 🏎️, 云端/本地 ☁️🏠, 多集群 K8s 管理 (SDK)。                                        |
| [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye)      | 用于 Kubernetes 管理的 MCP 服务器，分析集群和应用健康状况。                                   | 社区实现, Go 开发 🏎️, 云端/本地 ☁️🏠, K8s 管理与健康分析。                                         |
| [erikhoward/adls-mcp-server](https://github.com/erikhoward/adls-mcp-server) | 用于 Azure Data Lake Storage 的 MCP 服务器。可管理容器、读/写/上传/下载文件及管理元数据。   | 社区实现, Python 开发 🐍, 云端/本地 ☁️🏠, Azure Data Lake Storage 管理。                              |

---

### 🔍 搜索

*(让 AI 能够调用各种搜索引擎或专业搜索服务)*

| 名称                                                                 | 中文介绍                                                                                           | 备注                                                                                        |
| :------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| [Exa](https://github.com/exa-labs/exa-mcp-server)                    | Exa 官方集成，使用专为 AI 设计的 Exa 搜索引擎进行搜索。                                             | 官方实现 (Exa) 🎖️, TypeScript 开发 📇, 云服务 ☁️, AI 专用搜索引擎。                         |
| [Kagi Search](https://github.com/kagisearch/kagimcp)                 | Kagi 官方集成，使用 Kagi 的搜索 API 进行网页搜索。                                                 | 官方实现 (Kagi) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Kagi 搜索引擎。 (用户列表为Py, awesome为TS) |
| [Perplexity](https://github.com/ppl-ai/modelcontextprotocol)         | Perplexity 官方集成，连接 Perplexity Sonar API，实现实时全网研究。                                    | 官方实现 (Perplexity), Python 开发, Perplexity 实时搜索。                                   |
| [Search1API](https://github.com/fatwang2/search1api-mcp)             | Search1API 官方集成，一个 API 实现搜索、抓取和站点地图功能 (需付费 API Key)。                      | 官方实现 (Search1API), TypeScript 开发 📇, 云服务 ☁️, 多功能搜索 API。                     |
| [Tavily](https://github.com/tavily-ai/tavily-mcp)                    | Tavily 官方集成，专为 AI 代理设计的搜索引擎（搜索+提取）。                                           | 官方实现 (Tavily), Python 开发, AI 代理专用搜索引擎。                                       |
| [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) | AgentQL MCP 服务器，提供 AgentQL 的数据提取能力。                                           | 官方实现 (TinyFish IO) 🎖️, TypeScript 开发 📇, 云服务 ☁️, AgentQL 数据提取。             |
| [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) | Vectorize MCP 服务器，用于高级检索、私有深度研究、任意文件转 Markdown 提取和文本分块。        | 官方实现 (Vectorize) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 高级检索/RAG。                   |
| [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye)  | 通过 ZoomEye MCP 服务器查询网络资产信息。                                                   | 官方实现 (ZoomEye), TypeScript 开发 📇, 云服务 ☁️, 网络空间测绘搜索。                     |
| [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) | 官方参考实现，使用 Brave 的搜索 API 进行网页和本地搜索。                                           | 官方参考, TypeScript 开发 📇, 云服务 ☁️, Brave 搜索引擎。                                    |
| [0xdaef0f/job-searchoor](https://github.com/0xDAEF0F/job-searchoor)    | 用于搜索职位列表的 MCP 服务器，支持日期、关键词、远程工作选项等筛选。                            | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 职位搜索。                                      |
| [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi)  | Kagi 搜索 API 集成 (社区实现版本)。                                                       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Kagi 搜索 (社区 TS 版)。                         |
| [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) | 让 LLM 从 arXiv 搜索和阅读论文的 MCP。                                                 | 社区实现, Python 开发 🐍, 云服务 ☁️, arXiv 论文搜索。                                       |
| [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) | 让 LLM 从 PubMed 搜索和阅读医学/生命科学论文的 MCP。                                  | 社区实现, Python 开发 🐍, 云服务 ☁️, PubMed 论文搜索。                                    |
| [angheljf/nyt](https://github.com/angheljf/nyt)                      | 使用 NYTimes API 搜索文章。                                                            | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 纽约时报文章搜索。                                 |
| [Bigsy/Clojars-MCP-Server](https://github.com/Bigsy/Clojars-MCP-Server) | Clojars MCP 服务器，提供 Clojure 库的最新依赖信息。                                        | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Clojure 依赖搜索。                                |
| [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) | 搜索 ArXiv 研究论文。                                                                 | 社区实现, Python 开发 🐍, 云服务 ☁️, ArXiv 搜索 (另一版本)。                                |
| [chanmeng/google-news-mcp-server](https://github.com/ChanMeng666/server-google-news) | Google News 集成，自动主题分类，多语言支持，全面搜索能力 (SerpAPI)。                    | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Google News 搜索 (SerpAPI)。                   |
| [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) | 提供 OpenAI `web_search` 内置工具的 Python MCP 服务器。                                  | 社区实现, Python 开发 🐍, 本地/云端 🏠☁️, OpenAI 网页搜索模拟。                           |
| [devflowinc/trieve](https://github.com/devflowinc/trieve/tree/main/clients/mcp-server) | 通过 Trieve 爬取、嵌入、分块、搜索和检索数据集信息。                                      | 官方实现 (Trieve) 🎖️, TypeScript 开发 📇, 云端/本地 🏠☁️, Trieve RAG 平台。              |
| [Dumpling-AI/mcp-server-dumplingai](https://github.com/Dumpling-AI/mcp-server-dumplingai) | 访问 Dumpling AI 提供的数据、网页抓取和文档转换 API。                                    | 官方实现 (Dumpling AI) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Dumpling AI API 集成。           |
| [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn)                | 用于搜索 Hacker News、获取头条等的 MCP 服务器。                                            | 社区实现, Python 开发 🐍, 云服务 ☁️, Hacker News 搜索。                                   |
| [genomoncology/biomcp](https://github.com/genomoncology/biomcp)        | 生物医学研究服务器，提供对 PubMed、ClinicalTrials.gov 和 MyVariant.info 的访问。         | 社区实现, Python 开发 🐍, 云服务 ☁️, 生物医学信息搜索。                                     |
| [Google Custom Search](https://github.com/adenot/mcp-google-search)  | 通过 Google 自定义搜索 API 提供 Google 搜索结果。                                                | 社区实现, TypeScript 开发, Google 自定义搜索。                                            |
| [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) | 用于 Unsplash 图片搜索的 MCP 服务器。                                                  | 社区实现, Python 开发 🐍, 云服务 ☁️, Unsplash 图片搜索。                                  |
| [Ihor-Sokoliuk/MCP-SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng) | 连接到 SearXNG 元搜索引擎实例。                                                             | 社区实现, TypeScript 开发 📇, 本地/云端 🏠☁️, SearXNG 元搜索。                             |
| [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) | Naver 搜索 API 集成 MCP 服务器，支持博客、新闻、购物搜索和 DataLab 分析功能。               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Naver 搜索 (韩国)。                              |
| [Bing Web Search API](https://github.com/leehanchung/bing-search-mcp) | 微软必应网页搜索 API 的服务器实现。                                                             | 社区实现, Python 开发 🐍, Bing 搜索。 (Awesome列表为TS, 用户列表为Py, 可能有多个实现)           |
| [kshern/mcp-tavily](https://github.com/kshern/mcp-tavily.git)        | Tavily AI 搜索 API (社区实现版本)。                                                    | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Tavily 搜索 (社区 TS 版)。                        |
| [mzxrai/mcp-webresearch](https://github.com/mzxrai/mcp-webresearch)    | 搜索 Google 并在任何主题上进行深度网络研究。                                                | 社区实现, 搜索与研究。                                                                        |
| [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) | 使用 DuckDuckGo 进行网页搜索。                                                         | 社区实现, Python 开发 🐍, 云服务 ☁️, DuckDuckGo 搜索 (Python)。                            |
| [pskill9/web-search](https://github.com/pskill9/web-search)            | 无需 API Key，使用 Google 搜索结果进行免费网页搜索的 MCP 服务器。                           | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 免费 Google 搜索。                             |
| [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) | 提供类 OpenAI/Perplexity 自主深度研究、结构化查询细化和简洁报告的 MCP 服务器。              | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 自主深度研究。                                    |
| [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) | 连接到 searXNG 实例的 MCP 服务器 (社区实现版本)。                                         | 社区实现, Python 开发 🐍, 本地运行 🏠, SearXNG 元搜索 (Python)。                          |
| [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) | 获取 arXiv 论文的 LaTeX 源码，以处理数学内容和公式。                                   | 社区实现, Python 开发 🐍, 云服务 ☁️, arXiv LaTeX 源码获取。                                |
| [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) | 检索和处理来自 GeekNews 网站新闻数据的 MCP 服务器。                                      | 社区实现, Python 开发 🐍, 云服务 ☁️, GeekNews 新闻获取。                                  |
| [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) | Tavily AI 搜索 API (社区实现版本)。                                                    | 社区实现, Python 开发 🐍, 云服务 ☁️, Tavily 搜索 (社区 Py 版)。                            |
| [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mpc-server) | 提供 DuckDuckGo 搜索功能的基于 TypeScript 的 MCP 服务器。                               | 社区实现, TypeScript 开发 📇, 本地/云端 🏠☁️, DuckDuckGo 搜索 (TypeScript)。             |
| [mcp-local-rag](https://github.com/nkapila6/mcp-local-rag)           | 本地运行的 RAG 式网页搜索，使用 MediaPipe Embedder 和 DuckDuckGo。                               | 社区实现, Python 开发, 本地 RAG 搜索 (无需 API Key)。                                        |
| [douyin-mcp-server](https://github.com/yzfly/douyin-mcp-server)           | 提取抖音无水印视频链接，视频文案，douyin-mcp-server  | 社区实现, Python 开发, API 默认使用 [SiliconFlow API](https://cloud.siliconflow.cn/i/TxUlXG3u)                              |

---

### 💬 通讯与协作 (Slack, Email, Calendar, Social, etc.)

*(让 AI 能够收发消息、管理日程、参与团队协作等)*

| 名称                                                                 | 中文介绍                                                                                     | 备注                                                                                        |
| :------------------------------------------------------------------- | :------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| [agentmail-toolkit/mcp](https://github.com/agentmail-to/agentmail-toolkit/tree/main/mcp) | 用于即时创建收件箱以发送、接收和处理邮件的 MCP 服务器。专为 AI Agents 设计的邮件服务。 | 官方实现 (AgentMail) 🎖️, Python 开发 🐍, 邮件处理。                                       |
| [Inbox Zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) | Inbox Zero 官方集成，AI 个人邮件助手 (基于 Gmail，提供需回复/需跟进邮件识别等功能)。         | 官方实现 (Inbox Zero) 🎖️, Python 开发 🐍, 云服务 ☁️, 智能邮件管理。                       |
| [gotoHuman](https://github.com/gotohuman/gotohuman-mcp-server)       | gotoHuman 官方集成，允许 AI 代理和自动化向人类发送请求以供批准。                              | 官方实现 (gotoHuman), TypeScript 开发, 人机协作审批。                                     |
| [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) | 集成 Microsoft Teams 消息传递 (读/发/提及/列成员/线程) 的 MCP 服务器。              | 社区实现 (InditexTech), Python 开发 🐍, 云服务 ☁️, Microsoft Teams 集成。                  |
| [modelcontextprotocol/server-bluesky](https://github.com/keturiosakys/bluesky-context-server) | Bluesky 实例集成，用于查询和交互。                                                  | 官方参考 (推测, 在 MCP org 下), TypeScript 开发 📇, 云服务 ☁️, Bluesky 社交集成。       |
| [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) | 官方参考实现，集成 Slack，AI 能管理频道、发消息。                                            | 官方参考, TypeScript 开发 📇, 云服务 ☁️, Slack 团队协作。                                |
| [softeria/ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server) | 连接整个 Microsoft 365 套件 (Graph API)，包括邮件、文件、Excel、日历等的 MCP 服务器。 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Microsoft 365 全家桶集成。                     |
| [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp)       | Nostr MCP 服务器，允许与 Nostr 交互，发布笔记等。                                     | 社区实现, 云服务 ☁️, Nostr 社交协议集成。                                                 |
| [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit)          | 与 Twitter 搜索和时间线交互。                                                       | 社区实现, Python 开发 🐍, 云服务 ☁️, Twitter 交互。                                       |
| [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) | 与 Google Tasks API 交互的 MCP 服务器。                                            | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Google Tasks 管理 (TS)。                         |
| [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) | 安全地与 iMessage 数据库交互的 MCP 服务器，允许 LLM 查询分析对话 (含验证/附件/联系人/群聊/收发)。 | 社区实现, Go 开发 🏎️, 本地运行 🏠, macOS iMessage 集成 🍎。                              |
| [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp)    | Telegram API 集成，访问用户数据、管理对话、检索消息和处理已读状态。                       | 社区实现, Go 开发 🏎️, 本地运行 🏠, Telegram 集成 (Go)。                                  |
| [ClaudePost](https://github.com/ZilongXue/claude-post)               | 实现 Gmail 的无缝邮件管理，支持邮件搜索、阅读和发送。                                        | 社区实现, Python 开发, Gmail 邮件操作。                                                   |
| [Discord (by v-3)](https://github.com/v-3/discordmcp)                | 通过机器人连接 Discord 服务器，读写频道消息。                                                | 社区实现, TypeScript 开发, Discord 消息交互。                                             |
| [gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git) | 向企业微信群机器人发送各种类型消息的 MCP 服务器应用。                                  | 社区实现, Go 开发 🚀, 云服务 ☁️, 企业微信机器人。                                          |
| [Gmail](https://github.com/GongRzhe/Gmail-MCP-Server)                | 支持自动认证的 Gmail 集成，用于 Claude Desktop。                                           | 社区实现, Python 开发, Gmail 集成 (带认证)。                                             |
| [Gmail Headless](https://github.com/baryhuang/mcp-headless-gmail)    | 可远程托管的 Gmail 服务器，无需本地凭证或文件系统即可收发邮件。                                 | 社区实现, Python 开发, 远程 Gmail 操作。                                                |
| [Google Calendar (by v-3)](https://github.com/v-3/google-calendar)   | 集成 Google Calendar，检查日程、查找空闲时间、添加/删除事件。                                 | 社区实现, TypeScript 开发, Google 日历管理。                                              |
| [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) | 提供对 iMessage 数据库安全访问的 MCP 服务器 (FastMCP)，LLM 可查询分析对话 (含验证/附件)。 | 社区实现, Python 开发 🐍, 本地运行 🏠, macOS iMessage 集成 🍎 (FastMCP)。                |
| [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) | 提供对 Mattermost 团队、频道和消息访问的 MCP 服务器及主机。主机作为机器人集成，可配置 MCP 服务器。 | 社区实现, Python 开发 🐍, 本地运行 🏠, Mattermost 集成。                                    |
| [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp)      | 用于搜索个人 WhatsApp 消息、联系人以及向个人或群组发送消息的 MCP 服务器。                 | 社区实现, Python/Go 开发 🐍🏎️, WhatsApp 交互。                                          |
| [LINE](https://github.com/amornpan/py-mcp-line)                      | 集成 LINE Bot，让 AI 读取和分析 LINE 对话。                                                | 社区实现, Python 开发, LINE 对话分析。                                                  |
| [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) | Gmail 和 Google Calendar 集成。                                                    | 社区实现, Python 开发 🐍, 云服务 ☁️, Gmail/Google Calendar 集成。                         |
| [Apple Calendar](https://github.com/Omar-v2/mcp-ical)                | 与 macOS 日历交互，创建/修改事件、列出日程、查找空闲时段等。                                 | 社区实现, Python 开发 🐍, 本地运行 🏠, macOS 日历管理 🍎。                                  |
| [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp)          | 与 VRChat API 交互的 MCP 服务器。可获取好友、世界、虚拟形象等信息。                       | 社区实现, TypeScript 开发 📇, 本地运行 🏠, VRChat API 交互。                             |
| [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) | 与 Google Calendar API 交互的 MCP 服务器 (TypeScript 版)。                             | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Google Calendar 集成 (TS)。                       |
| [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp)          | 使用 ntfy 向手机发送通知的 MCP 服务器。                                                 | 社区实现, ntfy 通知。                                                                       |
| [Telegram](https://github.com/chigwell/telegram-mcp)                 | 通过 Telethon 集成 Telegram，支持分页读取聊天、检索和发送消息。                               | 社区实现, Python 开发, Telegram 消息交互。                                                |
| [userad/didlogic_mcp](https://github.com/UserAd/didlogic_mcp)          | DIDLogic MCP 服务器。增加管理 SIP 端点、号码和目的地的功能。                              | 社区实现, Python 开发 🐍, 云服务 ☁️, DIDLogic (VoIP) 集成。                               |
| [X (Twitter) (by vidhupv)](https://github.com/vidhupv/x-mcp)         | 直接通过 Claude 创建、管理和发布 X/Twitter 推文。                                            | 社区实现, Python 开发, Twitter 发推管理。                                                 |
| [Google Tasks (by zcaceres)](https://github.com/zcaceres/gtasks-mcp)   | Google Tasks API 服务器。                                                                   | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Google Tasks 管理 (TS)。                        |

---

### 💰 金融与加密货币

*(让 AI 能够获取金融数据、分析股票、与区块链交互等)*

| 名称                                                                               | 中文介绍                                                                                                | 备注                                                                                                         |
| :--------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------- |
| [BICScan](https://github.com/ahnlabio/bicscan-mcp)                                 | 获取 EVM 区块链地址（EOA, CA, ENS）甚至域名的风险评分/资产持有情况。 (BICScan 官方)                    | 官方实现 (AhnLab) 🎖️, Python 开发 🐍, 云服务 ☁️, 区块链地址风险分析。                                     |
| [Bankless Onchain](https://github.com/bankless/onchain-mcp)                        | 查询链上数据，如 ERC20 代币、交易历史、智能合约状态。 (Bankless 官方)                                   | 官方实现 (Bankless) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 链上数据查询。                                    |
| [base/base-mcp](https://github.com/base/base-mcp)                                  | Base Network 集成，提供链上工具，允许与 Base 网络和 Coinbase API 交互 (钱包/转账/合约/DeFi)。         | 官方实现 (Base/Coinbase) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Base 链与 Coinbase API。                      |
| [Chargebee](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol)  | Chargebee 官方集成，将 AI 代理连接到 Chargebee 计费平台。                                                 | 官方实现 (Chargebee) 🎖️, TypeScript 开发 📇, 云服务 ☁️, Chargebee 计费管理。                             |
| [codex-data/codex-mcp](https://github.com/Codex-Data/codex-mcp)                      | Codex API 集成，提供 60+ 网络上实时丰富的区块链和市场数据。                                        | 官方实现 (Codex Data) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 多链实时数据。                                 |
| [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp)        | Coinpaprika 的 DexPaprika MCP 服务器，暴露高性能 DexPaprika API (20+ 链/5M+ 代币/实时价格/流动性/历史数据)。 | 官方实现 (Coinpaprika) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 跨平台 🍎🪟🐧, DEX 聚合数据。                  |
| [Financial Datasets](https://github.com/financial-datasets/mcp-server)             | 专为 AI 代理设计的股票市场 API。                                                                        | 官方实现, Python 开发, AI 友好型股票数据。                                                                 |
| [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) | 访问 Heurist Mesh 网络中的专业 Web3 AI 代理 (区块链分析/合约安全/代币度量等)。 (Heurist 官方)           | 官方实现 (Heurist) 🎖️, Python 开发 🐍, 云端/本地 🏠☁️, Web3 AI 代理网络。                              |
| [Stripe](https://github.com/stripe/agent-toolkit)                                  | Stripe 官方集成，与 Stripe API 交互，处理支付、客户和退款。                                              | 官方实现 (Stripe), TypeScript 开发, Stripe 支付处理。                                                      |
| [Thirdweb](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp)       | Thirdweb 官方集成，读写 2000+ 区块链，查询数据、分析/部署合约、执行交易。                               | 官方实现 (Thirdweb), Python 开发, 多链区块链交互。                                                         |
| [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server)      | Coinmarket API 集成，获取加密货币列表和报价。                                                     | 社区实现, Python 开发 🐍, 云服务 ☁️, CoinMarketCap 数据。                                                |
| [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp)      | Alpha Vantage API 集成，获取股票和加密货币信息。                                                 | 社区实现, Python 开发 🐍, 云服务 ☁️, AlphaVantage 金融数据 (另一版本)。                                |
| [bitteprotocol/mcp](https://github.com/BitteProtocol/mcp)                          | Bitte Protocol 集成，在多个区块链上运行 AI Agents。                                              | 社区实现, TypeScript 开发 📇, Bitte Protocol 区块链 Agent。                                            |
| [Bsc-mcp](https://github.com/TermiX-official/bsc-mcp)                              | 连接 AI 与 BNB Chain，执行复杂的链上操作（转账、交易、安全检查等）。                                    | 社区实现, Python 开发, BNB Chain 操作。                                                                    |
| [EVM MCP Server](https://github.com/mcpdotdirect/evm-mcp-server)                   | 为 30+ EVM 网络提供全面的区块链服务，支持代币、NFT、智能合约、交易和 ENS。                                  | 社区实现, TypeScript 开发 📇, 云服务 ☁️, EVM 多链服务。                                                 |
| [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent)        | Yahoo Finance 集成，获取股市数据，包括期权推荐。                                                  | 社区实现, Python 开发 🐍, 云服务 ☁️, Yahoo Finance 数据与期权。                                         |
| [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent)              | Tastyworks API 集成，处理 Tastytrade 上的交易活动。                                               | 社区实现, Python 开发 🐍, 云服务 ☁️, Tastytrade 交易。                                                 |
| [getalby/nwc-mcp-server](https://github.com/getalby/nwc-mcp-server)                  | 由 Nostr Wallet Connect 驱动的比特币闪电网络钱包集成。                                             | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 比特币闪电网络钱包 (NWC)。                                  |
| [intentos-labs/beeper-mcp](https://github.com/intentos-labs/beeper-mcp)            | Beeper 在 BSC 上提供交易，包括余额/代币转移、Pancakeswap 代币交换和 beeper 奖励领取。                  | 社区实现, Python 开发 🐍, BSC 链交互 (Beeper)。                                                       |
| [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener)            | 使用开放免费的 Dexscreener API 获取实时链上市场价格。                                            | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Dexscreener 实时价格。                                         |
| [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp)      | 提供实时和历史的加密货币恐惧与贪婪指数数据。                                                      | 社区实现, Python 开发 🐍, 云服务 ☁️, 加密货币情绪指数。                                                  |
| [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp)    | 提供一系列加密货币技术分析指标和策略的 MCP 服务器。                                               | 社区实现, Python 开发 🐍, 云服务 ☁️, 加密货币技术指标。                                                  |
| [kukapay/crypto-portfolio-mcp](https://github.com/kukapay/crypto-portfolio-mcp)      | 用于跟踪和管理加密货币投资组合分配的 MCP 服务器。                                                 | 社区实现, Python 开发 🐍, 云服务 ☁️, 加密货币投资组合管理。                                              |
| [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp)      | 向 AI 代理提供加密货币情绪分析的 MCP 服务器。                                                   | 社区实现, Python 开发 🐍, 云服务 ☁️, 加密货币情绪分析。                                                  |
| [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server)    | 向 AI 代理提供最新加密货币新闻 (由 CryptoPanic 驱动)。                                           | 社区实现, Python 开发 🐍, 云服务 ☁️, CryptoPanic 新闻。                                                 |
| [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp)          | 将 Dune Analytics 数据桥接到 AI 代理的 MCP 服务器。                                             | 社区实现, Python 开发 🐍, 云服务 ☁️, Dune Analytics 集成。                                              |
| [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp)                  | 与 Freqtrade 加密货币交易机器人集成的 MCP 服务器。                                              | 社区实现, Python 开发 🐍, 云服务 ☁️, Freqtrade 交易机器人集成。                                          |
| [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp)                      | 使用 Jupiter 的新 Ultra API 在 Solana 区块链上执行代币交换的 MCP 服务器。                         | 社区实现, Python 开发 🐍, 云服务 ☁️, Solana Jupiter 交易 (Ultra API)。                              |
| [kukapay/pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp) | 跟踪 Pancake Swap 上新创建池子的 MCP 服务器。                                                   | 社区实现, Python 开发 🐍, 云服务 ☁️, PancakeSwap 新池子监控。                                          |
| [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp)                  | 检测 Solana meme 代币潜在风险的 MCP 服务器。                                                    | 社区实现, Python 开发 🐍, 云服务 ☁️, Solana Meme 币风险检测。                                          |
| [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp)                    | 用来自 The Graph 的索引化区块链数据赋能 AI 代理的 MCP 服务器。                                  | 社区实现, Python 开发 🐍, 云服务 ☁️, The Graph 数据集成。                                               |
| [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp)              | 为 AI 代理提供在多个区块链上铸造 ERC-20 代币工具的 MCP 服务器。                                   | 社区实现, Python 开发 🐍, 云服务 ☁️, 多链 ERC-20 铸造。                                                 |
| [kukapay/token-revoke-mcp](https://github.com/kukapay/token-revoke-mcp)              | 用于检查和撤销多个区块链上 ERC-20 代币授权的 MCP 服务器。                                         | 社区实现, Python 开发 🐍, 云服务 ☁️, 多链 ERC-20 授权管理。                                             |
| [kukapay/uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp)        | 跟踪多个区块链上 Uniswap 新创建流动性池的 MCP 服务器。                                            | 社区实现, Python 开发 🐍, 云服务 ☁️, Uniswap 新池子监控 (多链)。                                        |
| [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp)          | 用于 AI 代理在多个区块链上自动化 Uniswap DEX 代币交换的 MCP 服务器。                              | 社区实现, Python 开发 🐍, 云服务 ☁️, Uniswap 自动交易 (多链)。                                          |
| [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp)            | 用于跟踪加密货币巨鲸交易的 MCP 服务器。                                                       | 社区实现, Python 开发 🐍, 云服务 ☁️, 加密货币巨鲸追踪。                                                  |
| [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp)                          | Alpaca 交易 API 的 MCP 服务器，用于管理股票和加密货币投资组合、下单和访问市场数据。                  | 社区实现, Python 开发 🐍, 云服务 ☁️, Alpaca 交易 API 集成。                                            |
| [longportapp/openapi](https://github.com/longportapp/openapi/tree/main/mcp)        | LongPort OpenAPI 提供实时股市数据，通过 MCP 为 AI 提供分析和交易能力。                          | 官方实现 (LongPort) 🎖️, Python 开发 🐍, 云服务 ☁️, LongPort 股票数据与交易。                           |
| [mcpdotdirect/starknet-mcp-server](https://github.com/mcpdotdirect/starknet-mcp-server) | 全面的 Starknet 区块链集成，支持原生代币 (ETH, STRK)、智能合约、StarknetID 解析和代币转移。       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Starknet 全功能集成。                                       |
| [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger)        | ledger-cli 集成，用于管理金融交易和生成报告。                                                    | 社区实现, Python 开发 🐍, 本地运行 🏠, ledger-cli 记账。                                            |
| [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp)              | 使用 Yahoo Finance API 获取金融数据，方便进行股票分析。                                                  | 社区实现, Python 开发 🐍, 云服务 ☁️, Yahoo Finance 数据获取。                                          |
| [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx)                          | 核心银行集成，用于管理客户、贷款、储蓄、股份、金融交易和生成财务报告。                                | 社区实现 (OpenMF), 云端/本地 ☁️🏠, Mifos X 核心银行系统集成。                                        |
| [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server)              | Bitget API 获取加密货币价格。                                                                | 社区实现, Python 开发 🐍, 云服务 ☁️, Bitget 价格获取。                                                |
| [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp)            | 使用 CoinCap 公共 API 的实时加密货币市场数据集成，无需 API Key 即可访问价格和市场信息。              | 社区实现, TypeScript 开发 📇, 云服务 ☁️, CoinCap 实时数据。                                          |
| [SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop.git) | 使用 CoinGecko API 提供加密货币市场数据的 MCP 工具。                                          | 社区实现, Python 开发 🐍, 云服务 ☁️, CoinGecko 数据。                                               |
| [SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop.git) | 使用 Yahoo Finance API 提供股市数据和分析的 MCP 工具。                                          | 社区实现, Python 开发 🐍, 云服务 ☁️, Yahoo Finance 数据分析。                                       |
| [Solana Agent Kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) | 使用 Solana Agent Kit 与 Solana 区块链交互，支持 40+ 协议操作。                                        | 社区实现, TypeScript 开发, Solana 链交互。                                                         |
| [AlphaVantage](https://github.com/calvernaz/alphavantage)                          | AlphaVantage 股票市场数据 API 服务器。                                                              | 社区实现, Python 开发, AlphaVantage 金融数据。                                                      |

---

### 📁 文件系统与存储

*(让 AI 能够访问本地文件、操作云存储等)*

| 名称                                                                               | 中文介绍                                                                                           | 备注                                                                                                |
| :--------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------- |
| [Box](https://github.com/box-community/mcp-server-box)                             | Box 官方集成，通过 Box AI 与智能内容管理平台交互。                                                 | 官方实现 (Box Community) 🎖️, Python 开发, Box 云存储交互。                                      |
| [Fireproof](https://github.com/fireproof-storage/mcp-database-server)              | Fireproof 官方集成，不可变账本数据库，支持实时同步。 (也含数据库功能)                                 | 官方实现 (Fireproof) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 分布式数据库/存储同步。                 |
| [microsoft/markitdown](https://github.com/microsoft/markitdown/tree/main/packages/markitdown-mcp) | MarkItDown MCP 工具访问 - 一个将多种文件格式（本地或远程）转换为 Markdown 以供 LLM 使用的库。      | 官方实现 (Microsoft) 🎖️, Python 开发 🐍, 本地运行 🏠, 文件转 Markdown。                           |
| [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal)            | 使用 Apache OpenDAL™ 访问任何存储。                                                          | 社区实现, Python 开发 🐍, 本地/云端 🏠☁️, Apache OpenDAL 通用存储访问。                           |
| [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | 官方参考实现，提供对本地文件系统的直接访问，带可配置权限。                                             | 官方参考, TypeScript 开发 📇, 本地运行 🏠, 本地文件系统操作。                                   |
| [modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) | 官方参考实现，集成 Google Drive，用于列出、读取和搜索文件。                                        | 官方参考, TypeScript 开发 📇, 云服务 ☁️, Google Drive 文件管理。                                |
| [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian)                | 读取和搜索 Obsidian 库或任何包含 Markdown 笔记的目录。                                             | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Obsidian/Markdown 文件访问。                          |
| [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py)          | 通过 MCP 或剪贴板与 LLM 共享代码上下文。                                                      | 社区实现, Python 开发 🐍, 本地运行 🏠, 代码上下文共享。                                           |
| [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger)      | 文件合并工具，适用于 AI 聊天长度限制。                                                        | 社区实现, Go 开发 🏎️, 本地运行 🏠, 文件合并。                                                  |
| [filesystem@quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/filesystem) | 使用 Quarkus 在 Java 中实现的允许浏览和编辑文件系统。可用作 jar 或原生镜像。                       | 社区实现 (Quarkiverse), Java 开发 ☕, 本地运行 🏠, Java 文件系统操作。                           |
| [Golang Filesystem Server](https://github.com/mark3labs/mcp-filesystem-server)     | Go 语言实现的安全文件操作，带可配置访问控制。                                                        | 社区实现, Go 开发 🏎️, 本地运行 🏠, 本地文件系统操作 (Go)。                                       |
| [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server)                        | Box 集成，用于列出、读取和搜索文件 (社区实现版本)。                                           | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Box 文件操作 (社区 TS 版)。                           |
| [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) | 在 Windows 上使用 Everything SDK 快速搜索文件。 (Awesome列表更通用)                               | 社区实现, Python 开发 🐍, 本地运行 🏠, Windows 快速文件搜索 🪟。                              |
| [Everything Search (mamertofabian)](https://github.com/mamertofabian/mcp-everything-search) | [更新] 在 Windows/macOS/Linux 上快速搜索文件（使用 Everything/mdfind/locate）。 (更新自Awesome列表描述) | 社区实现, Python 开发 🐍, 本地运行 🏠, 跨平台 🪟🍎🐧 快速文件搜索。                         |

---

### 📊 数据分析、处理与可视化

*(让 AI 能够处理表格数据、生成图表、进行数据探索等)*

| 名称                                                                 | 中文介绍                                                                                                 | 备注                                                                                                         |
| :------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------- |
| [Axiom](https://github.com/axiomhq/mcp-server-axiom)                 | Axiom 官方集成，用自然语言查询和分析 Axiom 日志、追踪等事件数据。                                           | 官方实现 (Axiom), Python 开发, Axiom 日志分析。                                                              |
| [Comet Opik](https://github.com/comet-ml/opik-mcp)                   | Comet 官方集成，用自然语言查询和分析 Opik 日志、追踪、提示等 LLM 遥测数据。                               | 官方实现 (Comet ML) 🎖️, TypeScript 开发 📇, 云端/本地 🏠☁️, LLM 可观测性数据分析。                        |
| [flowcore/mcp-flowcore-platform](https://github.com/flowcore-io/mcp-flowcore-platform) | 与 Flowcore 交互以执行操作、摄取数据，并分析、交叉引用和利用数据核心中的任何数据。                       | 官方实现 (Flowcore) 🎖️, TypeScript 开发 📇, 云端/本地 🏠☁️, Flowcore 数据平台交互。                 |
| [GreptimeDB](https://github.com/GreptimeTeam/greptimedb-mcp-server)  | GreptimeDB 官方集成，让 AI 安全地探索和分析 GreptimeDB 中的时序数据。(已在数据库部分列出)                    | 官方实现 (Greptime) 🎖️, Python 开发 🐍, 本地运行 🏠, GreptimeDB 时序数据分析。                           |
| [JordiNei/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) | 连接到 Databricks API，允许 LLM 运行 SQL 查询、列出作业和获取作业状态。                             | 社区实现, Databricks API 集成。                                                                            |
| [jwaxman19/qlik-mcp](https://github.com/jwaxman19/qlik-mcp)            | Qlik Cloud API 的 MCP 服务器，支持查询应用、工作表和从可视化中提取数据 (带认证和速率限制)。               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Qlik Cloud API 集成。                                          |
| [Keboola](https://github.com/keboola/keboola-mcp-server)             | Keboola 官方集成，在单一平台上构建数据工作流、集成和分析。                                                  | 官方实现 (Keboola) 🎖️, Python 开发, Keboola 数据平台。                                                    |
| [yzfly/mcp-excel-server](https://github.com/yzfly/mcp-excel-server)  | 通过自然语言与 Excel 交互的 MCP 服务器。                                                                 | 社区标杆, Excel 读写、分析、可视化。                                                                       |
| [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) | 使用 Chronulus AI 预测和预测代理预测任何事物。                                                     | 社区实现, Python 开发 🐍, 云服务 ☁️, AI 预测服务。                                                         |
| [Excel (by haris-musa)](https://github.com/haris-musa/excel-mcp-server) | Excel 操作，包括读写、工作表管理、格式化、图表和数据透视表 (提供更高级的功能)。                               | 社区实现, Python 开发 🐍, 本地运行 🏠, Excel 高级操作。                                                  |
| [Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) | 对 .csv 数据集进行自主数据探索，轻松获得智能见解（**注意：会执行代码**）。                               | 社区实现, Python 开发 🐍, 云服务 ☁️, CSV 数据自动探索。                                                  |
| [Dataset Viewer](https://github.com/privetin/dataset-viewer)         | 浏览和分析 Hugging Face 数据集，支持搜索、过滤、统计和导出。                                             | 社区实现, Python 开发, HuggingFace 数据集浏览。                                                          |
| [Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)   | 使用 Vega-Lite 格式和渲染器从获取的数据生成可视化图表。                                                    | 社区实现, Python 开发 🐍, 本地运行 🏠, 数据可视化生成。                                                 |
| [QuickChart](https://github.com/GongRzhe/Quickchart-MCP-Server)      | 使用 QuickChart.io 生成图表。                                                                           | 社区实现, Python 开发, 图表生成服务。                                                                    |
| [Mindmap](https://github.com/YuChenSSR/mindmap-mcp-server)           | 从包含 Markdown 代码的输入生成美观的交互式思维导图。                                                       | 社区实现, Python 开发 🐍, 本地运行 🏠, 思维导图生成。                                                 |
| [JSON](https://github.com/GongRzhe/JSON-MCP-Server)                  | JSON 处理服务器，支持 JSONPath 查询和多种操作。                                                            | 社区实现, Python 开发, 高级 JSON 处理。                                                                 |
| [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) | 将几乎任何文件或 Web 内容转换为 Markdown 的 MCP 服务器。                                          | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 文件/网页转 Markdown。                                      |

---

### 🛠️ 效率工具与集成 (Office, Project Management, Notes, etc.)

*(让 AI 能够使用日历、任务管理、项目管理、笔记等工具)*

| 名称                                                                       | 中文介绍                                                                                                 | 备注                                                                                                          |
| :------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------ |
| [Dart](https://github.com/its-dart/dart-mcp-server)                        | Dart 官方集成，与 AI 原生项目管理工具 Dart 中的任务、文档、项目数据交互。                                   | 官方实现 (Dart) 🎖️, TypeScript 开发 📇, Dart 项目管理。                                                    |
| [Fibery](https://github.com/Fibery-inc/fibery-mcp-server)                  | Fibery 官方集成，在 Fibery 工作区中执行查询和实体操作。                                                    | 官方实现 (Fibery) 🎖️, TypeScript 开发 📇, Fibery 工作管理。                                                  |
| [Make](https://github.com/integromat/make-mcp-server)                      | Make 官方集成，将 Make 场景转换为 AI 助手可调用的工具。                                                    | 官方实现 (Make/Integromat) 🎖️, TypeScript 开发 📇, 本地运行 🏠, 连接 Make 生态。                         |
| [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol) | Pipedream 官方集成，一站式连接 2500+ API，集成 8000+ 工具，并管理用户服务器。                            | 官方实现 (Pipedream) 🎖️, Node.js 开发, 云端/本地 ☁️🏠, 超强 API/工具集成平台。                     |
| [Rember](https://github.com/rember/rember-mcp)                             | 在 Rember 中创建间隔重复抽认卡，记住聊天中学到的任何东西。 (Rember 官方)                                    | 官方实现 (Rember) 🎖️, TypeScript 开发 📇, 本地运行 🏠, 间隔重复记忆工具。                               |
| [Zapier](https://zapier.com/mcp)                                           | Zapier 官方集成，将 AI 代理即时连接到 8000+ 应用。                                                       | 官方实现 (Zapier), 连接 Zapier 生态。                                                                        |
| [Airtable (by domdomegg)](https://github.com/domdomegg/airtable-mcp-server) | 读写 Airtable 数据库，带模式检查。(已在数据库部分列出)                                                     | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Airtable 读写。                                                  |
| [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server)          | 允许 AI 读取你的 Bear 笔记 (仅 macOS)。                                                            | 社区实现, macOS Bear 笔记读取 🍎.                                                                          |
| [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) | 用于基本本地 taskwarrior 使用的 MCP 服务器 (添加/更新/删除任务)。                                  | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Taskwarrior 任务管理。                                        |
| [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp)              | 与 Notion API 集成以高效管理个人待办事项列表的 MCP 服务器。                                          | 社区实现, Python 开发 🐍, 云服务 ☁️, Notion ToDo 管理 (Python)。                                         |
| [bart6114/my-bear-mcp-server](https://github.com/bart6114/my-bear-mcp-server/) | 允许通过直接与 Bear 的 SQLite 数据库集成来读取 Bear 笔记应用的笔记和标签。                               | 社区实现, TypeScript 开发 📇, 本地运行 🏠, macOS Bear 笔记读取 🍎 (SQLite 直连)。                       |
| [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp)              | 与 Notion API 集成以管理个人待办事项列表。                                                          | 社区实现, Python 开发 🐍, 云服务 ☁️, Notion ToDo 管理 (Python, 另一版本)。                                |
| [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro)                  | 访问 MIRO 白板，批量创建和读取项目。需要 REST API 的 OAUTH 密钥。                                   | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Miro 白板交互。                                                |
| [fradser/mcp-server-apple-reminders](https://github.com/FradSer/mcp-server-apple-reminders) | 用于与 macOS 上的 Apple Reminders 交互的 MCP 服务器。                                            | 社区实现, TypeScript 开发 📇, 本地运行 🏠, macOS Reminders 管理 🍎。                               |
| [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) | 允许 LLM 使用 MCP 与 Raindrop.io 书签交互的集成。                                                 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Raindrop.io 书签管理。                                       |
| [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server)            | 允许 AI 客户端在 Attio CRM 中管理记录和笔记。                                                       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Attio CRM 管理。                                                |
| [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp)        | 在 Contentful Space 中更新、创建、删除内容、内容模型和资产。                                          | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Contentful CMS 管理。                                        |
| [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) | 此 MCP 服务器将帮助您通过 Plane 的 API 管理项目和问题。                                             | 社区实现, Go 开发 🏎️, 本地运行 🏠, Plane 项目管理。                                                    |
| [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro)                  | Miro MCP 服务器，暴露官方 Miro SDK 中可用的所有功能。                                               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Miro 白板交互 (更全面)。                                      |
| [kj455/mcp-kibela](https://github.com/kj455/mcp-kibela)                      | 允许 AI 模型与 Kibela 交互。                                                                     | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Kibela 知识库交互。                                          |
| [KS-GEN-AI/confluence-mcp-server](https://github.com/KS-GEN-AI/confluence-mcp-server) | 通过 CQL 获取 Confluence 数据并阅读页面。                                                           | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 跨平台 🍎🪟, Confluence 数据读取。                          |
| [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server)      | 通过 JQL 和 API 读取 Jira 数据，并执行请求以创建和编辑工单。                                         | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 跨平台 🍎🪟, Jira 数据读写。                             |
| [lciesielski/mcp-salesforce](https://github.com/lciesielski/mcp-salesforce-example) | 具有与 Salesforce 实例交互基本演示的 MCP 服务器。                                                  | 社区实现, 本地/云端 🏠☁️, Salesforce 集成示例。                                                     |
| [Linear (by jerhadf)](https://github.com/jerhadf/linear-mcp-server)        | 与 Linear API 交互进行项目管理，包括搜索、创建和更新 Issues。                                            | 社区实现, TypeScript 开发, Linear 项目管理。                                                        |
| [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) | 通过 REST API 与 Obsidian 交互。                                                               | 社区实现, Python 开发 🐍, 云端/本地 🏠☁️, Obsidian REST API 交互。                                 |
| [Notion (by v-3)](https://github.com/v-3/notion-server)                    | Notion 集成，通过 Claude 搜索、读取、更新和创建页面。                                                    | 社区实现, TypeScript 开发 📇, Notion 页面管理。                                                      |
| [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) | 与 Apple Shortcuts 集成的 MCP 服务器。                                                         | 社区实现, TypeScript 开发 📇, 本地运行 🏠, macOS Apple Shortcuts 集成 🍎。                       |
| [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana)        | Asana 的 MCP 服务器实现，允许从 MCP 客户端与 Asana API 对话。                                       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Asana 项目管理。                                            |
| [sirmews/apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp)          | 允许 AI 从本地 Apple Notes 数据库读取 (仅 macOS)。                                               | 社区实现, Python 开发 🐍, 本地运行 🏠, macOS Apple Notes 读取 🍎。                                 |
| [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian)          | Atlassian 产品 (Confluence 和 Jira) 的 MCP 服务器。支持 Cloud/Server/DC。提供全面的工具用于搜索、读取、创建和管理内容。 | 社区实现, Python 开发 🐍, 云服务 ☁️, Confluence/Jira 全功能管理。                                 |
| [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server)          | 与 Notion API 交互。                                                                           | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Notion API 交互 (另一版本)。                           |
| [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear)          | 与 Linear 项目管理系统集成。                                                                     | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 跨平台 🍎🪟🐧, Linear 项目管理 (另一版本)。              |
| [Todoist](https://github.com/abhiz123/todoist-mcp-server)                  | 与 Todoist 交互来管理你的任务。                                                                         | 社区实现, Python 开发, Todoist 任务管理。                                                            |
| [Home Assistant (by tevonsb)](https://github.com/tevonsb/homeassistant-mcp)  | 与 Home Assistant 交互，查看和控制灯光、开关、传感器等智能家居设备。                                      | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 智能家居控制。                                          |
| [allenporter/mcp-server-home-assistant](https://github.com/allenporter/mcp-server-home-assistant) | 通过 MCP 服务器暴露所有 Home Assistant 语音意图，实现家庭控制。                                  | 社区实现, Python 开发 🐍, 本地运行 🏠, Home Assistant 语音控制。                                    |
| [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp)                | 允许 AI 模型与 HackMD 交互。                                                                   | 社区实现, TypeScript 开发 📇, 云服务 ☁️, HackMD 协作笔记。                                       |
| [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp)                | 文颜 MCP Server， 让 AI 将 Markdown 文章自动排版后发布至微信公众号。                                                                   | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 推荐 Docker 部署。                                       |

---

###  multimedia 多媒体与内容创作

*(让 AI 能够生成动画、编辑视频、处理图像、语音合成等)*

| 名称                                                                               | 中文介绍                                                                                                   | 备注                                                                                                         |
| :--------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------- |
| [Amazon Bedrock Nova Canvas](https://github.com/zxkane/mcp-server-amazon-bedrock)    | 使用 Amazon Nova Canvas 模型进行图像生成。                                                            | 社区实现, TypeScript 开发 📇, 云服务 ☁️, AWS Bedrock 图像生成。                                           |
| [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server)      | PiAPI MCP 服务器使用户能够直接从 Claude 或任何其他 MCP 兼容应用生成 Midjourney/Flux/Kling/Hunyuan/Udio/Trellis 等媒体内容。 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 多模型媒体内容生成 (PiAPI)。                                    |
| [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server)            | 用 Manim 生成动画，适合制作数学、科技类可视化内容。                                                          | 社区实现, Python 开发 🐍, 本地运行 🏠, 跨平台 🪟🐧, 数学/科技动画。                                        |
| [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp)            | 提供通过 Replicate API 生成图像的能力。                                                               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Replicate 图像生成 (Flux)。                                      |
| [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp)    | 视频编辑神器，支持添加、分析、搜索和生成视频剪辑。                                                           | 社区实现, Python 开发 🐍, 视频内容创作。                                                                   |
| [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp)                      | 使用 Aseprite API 创建像素艺术的 MCP 服务器。                                                         | 社区实现, Python 开发 🐍, 本地运行 🏠, Aseprite 像素艺术。                                                |
| [EverArt](https://github.com/modelcontextprotocol/servers/tree/main/src/everart)   | 官方参考实现，使用多种模型进行 AI 图像生成。                                                               | 官方参考, TypeScript 开发, AI 图像生成。                                                                    |
| [ElevenLabs](https://github.com/mamertofabian/elevenlabs-mcp-server)             | 集成 ElevenLabs TTS API，能生成包含多种声音的完整画外音。                                                | 社区实现, Python 开发, 文本转语音 TTS。                                                                    |
| [Image Generation](https://github.com/GongRzhe/Image-Generation-MCP-Server)        | 使用 Replicate Flux 模型提供图像生成能力。                                                                 | 社区实现, Python 开发, AI 图像生成 (Replicate)。                                                            |
| [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) | 用于本地压缩各种图像格式的 MCP 服务器。                                                               | 社区实现, Python 开发 🐍, 本地运行 🏠, 图像压缩。                                                         |
| [j3k0/speech.sh](https://github.com/j3k0/speech.sh/blob/main/MCP_README.md)        | 让代理大声说出内容，并在工作完成时用简短摘要通知你。                                                    | 社区实现, 本地运行 🏠, 语音输出/通知。                                                                    |
| [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) | 获取 YouTube 字幕和转录文本供 AI 分析。                                                               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, YouTube 字幕/转录。                                             |
| [Replicate](https://github.com/deepfates/mcp-replicate)                          | 在 Replicate 上搜索、运行和管理机器学习模型，处理生成的图像。                                               | 社区实现, TypeScript 开发, Replicate 模型调用。                                                             |
| [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) | DaVinci Resolve 的 MCP 服务器集成，提供视频编辑、调色、媒体管理和项目控制的强大工具。                     | 社区实现, Python 开发 🐍, DaVinci Resolve 视频编辑。                                                     |
| [YouTube](https://github.com/ZubeidHendricks/youtube-mcp-server)                 | 全面的 YouTube API 集成，用于视频管理、Shorts 创建和分析。                                                   | 社区实现, Python 开发, YouTube 管理与分析。                                                             |
| [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube)              | 获取 YouTube 字幕 (另一版本)。                                                                    | 社区实现, TypeScript 开发 📇, 云服务 ☁️, YouTube 字幕。                                                  |

---

### 🧠 知识、记忆与 RAG

*(让 AI 拥有长期记忆、能够基于特定知识库回答问题等)*

| 名称                                                                               | 中文介绍                                                                                                         | 备注                                                                                                    |
| :--------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------ |
| [Graphlit](https://github.com/graphlit/graphlit-mcp-server)                      | Graphlit 官方集成，将各种来源（Slack, Gmail, 播客等）内容摄入可搜索的 Graphlit 项目。                            | 官方实现 (Graphlit) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 多源内容 RAG。                                |
| [Inkeep](https://github.com/inkeep/mcp-server-python)                            | Inkeep 官方集成，基于 Inkeep 的 RAG 搜索你的内容。                                                               | 官方实现 (Inkeep), Python 开发, Inkeep RAG 搜索。                                                     |
| [Needle](https://github.com/needle-ai/needle-mcp)                                | Needle 官方集成，提供开箱即用的生产级 RAG，用于搜索和检索自有文档。                                              | 官方实现 (Needle AI), TypeScript 开发, 生产级 RAG。                                                   |
| [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp)          | 连接到你的 Pinecone Assistant，并从其知识引擎中为 Agent 提供上下文。                                          | 官方实现 (Pinecone) 🎖️, Rust 开发 🦀, 云服务 ☁️, Pinecone Assistant RAG。                           |
| [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | 官方参考实现，基于知识图谱的持久记忆系统。                                                                       | 官方参考, TypeScript 开发 📇, 本地运行 🏠, 知识图谱记忆。                                            |
| [Basic Memory](https://github.com/basicmachines-co/basic-memory)                 | 本地优先的知识管理系统，从 Markdown 文件构建语义图，实现跨对话持久记忆。                                           | 社区实现, TypeScript 开发, 本地 Markdown 知识图谱记忆。                                               |
| [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh)                | 增强的基于图的记忆，专注于 AI 角色扮演和故事生成。                                                          | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 图记忆 (角色扮演/故事)。                                 |
| [cognee-mcp](https://github.com/topoteretes/cognee/tree/main/cognee-mcp)           | GraphRAG 记忆服务器，支持自定义摄取、数据处理和搜索。                                                            | 社区实现, TypeScript 开发 📇, 本地运行 🏠, GraphRAG 记忆。                                            |
| [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp)          | 实现 Zettelkasten 知识管理方法的 MCP 服务器，允许通过 Claude 等客户端创建、链接和搜索原子笔记。                     | 社区实现, Python 开发 🐍, 本地运行 🏠, Zettelkasten 笔记法。                                        |
| [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs)           | 提供通过向量搜索检索和处理文档工具的 MCP 服务器实现，使 AI 助手能用相关文档上下文增强响应。                           | 社区实现, Python 开发 🐍, 本地运行 🏠, 文档 RAG (向量搜索)。                                        |
| [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero)                      | 让 LLM 与 Zotero Cloud 上的收藏和文献来源交互的连接器。                                                   | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Zotero 文献管理。                                           |
| [mcp-summarizer](https://github.com/0xshellming/mcp-summarizer)                    | AI 摘要 MCP 服务器，支持多种内容类型：纯文本、网页、PDF 文档、EPUB 书籍、HTML 内容。                        | 社区实现, Go 开发 📕, 云服务 ☁️, 多格式内容摘要。                                                    |
| [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp)                            | 管理代码偏好和模式，支持语义搜索，方便在 IDE 中存取技术文档。 (Mem0 官方) (已在开发工具列出)                        | 官方实现 (Mem0 AI) 🎖️, Python 开发 🐍, 本地运行 🏠, 程序员的记忆助手和偏好管理。                   |
| [Minima](https://github.com/dmayboroda/minima)                                   | 用于本地文件 RAG 的 MCP 服务器。                                                                               | 社区实现, Python 开发, 本地文件 RAG。                                                               |
| [Rememberizer AI](https://github.com/skydeckai/mcp-server-rememberizer)            | 与 Rememberizer 数据源交互，促进增强的知识检索。                                                                 | 社区实现, Python 开发, 知识检索。                                                                 |
| [topoteretes/cognee](https://github.com/topoteretes/cognee/tree/dev/cognee-mcp)     | 使用各种图和向量存储的 AI 应用和 Agents 记忆管理器，允许从 30+ 数据源摄取。 (cognee-mcp 的开发分支)              | 社区实现, TypeScript 开发 📇, 本地运行 🏠, GraphRAG 记忆 (更通用)。                                  |
| [unibaseio/membase-mcp](https://github.com/unibaseio/membase-mcp)                  | 通过 Membase 以分布式方式保存和查询你的 Agent 记忆。                                                     | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 分布式 Agent 记忆。                                      |

---

### 🔒 安全与分析

*(让 AI 能够进行安全扫描、二进制分析、风险评估等)*

| 名称                                                                               | 中文介绍                                                                                              | 备注                                                                                                     |
| :--------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------- |
| [BICScan](https://github.com/ahnlabio/bicscan-mcp)                                 | 获取 EVM 区块链地址（EOA, CA, ENS）甚至域名的风险评分/资产持有情况。 (BICScan 官方) (已在金融部分列出)       | 官方实现 (AhnLab) 🎖️, Python 开发 🐍, 云服务 ☁️, 区块链地址风险分析。                                 |
| [Semgrep](https://github.com/semgrep/mcp)                                        | Semgrep 官方集成，让 AI 代理使用 Semgrep 进行代码安全扫描。 (已在开发工具列出)                            | 官方实现 (Semgrep) 🎖️, TypeScript 开发 📇, 云服务 ☁️, 代码安全扫描。                                 |
| [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP)                                | 集成 Ghidra 进行二进制分析，支持函数检查、反编译、内存探索、导入/导出分析等。                              | 社区实现, Python+Java 开发 🐍☕, 本地运行 🏠, 二进制逆向工程 (Ghidra)。                               |
| [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) | 用于分析来自 Azure 租户枚举的 ROADrecon 收集结果的 MCP 服务器。                                   | 社区实现, Python 开发 🐍, Windows 本地 🪟🏠, Azure AD 分析 (ROADrecon)。                            |
| [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist)            | dnstwist MCP 服务器，强大的 DNS 模糊测试工具，帮助检测域名抢注、钓鱼和企业间谍活动。                   | 社区实现, TypeScript 开发 📇, Windows/云端 🪟☁️, DNS Fuzzing (dnstwist)。                          |
| [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret)              | maigret MCP 服务器，强大的 OSINT 工具，从各种公共来源收集用户账户信息。提供跨社交网络搜索用户名和分析 URL 的工具。 | 社区实现, TypeScript 开发 📇, Windows/云端 🪟☁️, OSINT (maigret)。                                |
| [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan)                | 用于查询 Shodan API 和 Shodan CVEDB 的 MCP 服务器。提供 IP 查找、设备搜索、DNS 查找、漏洞查询等工具。    | 社区实现, TypeScript 开发 📇, Windows/云端 🪟☁️, Shodan API 查询。                                |
| [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal)        | 用于查询 VirusTotal API 的 MCP 服务器。提供扫描 URL、分析文件哈希和检索 IP 地址报告的工具。              | 社区实现, TypeScript 开发 📇, Windows/云端 🪟☁️, VirusTotal API 查询。                            |
| [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp)        | Binary Ninja 插件、MCP 服务器和桥接器，无缝集成 Binary Ninja 与 MCP 客户端，自动化二进制分析和逆向工程。 | 社区实现, Python 开发 🐍, 本地运行 🏠, 跨平台 🍎🪟🐧, 二进制分析 (Binary Ninja)。                 |
| [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security)                  | 用于查询 ORKL API 的 MCP 服务器。提供获取威胁报告、分析威胁行为者和检索情报来源的工具。                 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 威胁情报 (ORKL API)。                                       |
| [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp)                    | Volatility 3.x 的 MCP 服务器，允许使用 AI 助手执行内存取证分析。通过 REST API 和 LLM 使 pslist 和 netscan 等插件易于访问。 | 社区实现, 内存取证 (Volatility)。                                                                   |
| [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) | 访问 Heurist Mesh 网络中的专业 Web3 AI 代理，进行区块链分析、智能合约安全、代币度量等。 (已在金融部分列出)          | 官方实现 (Heurist) 🎖️, Python 开发 🐍, 云端/本地 🏠☁️, Web3 安全与分析。                            |
| [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp)                    | IDA Pro 的 MCP 服务器，允许使用 AI 助手执行二进制分析。此插件实现反编译、反汇编，并允许自动生成恶意软件分析报告。 | 社区实现, Python 开发 🐍, 本地运行 🏠, 二进制逆向工程 (IDA Pro)。                                 |
| [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon)                  | 由 httpx 和 asnmap 驱动的对话式侦察接口和 MCP 服务器。支持不同级别的域分析、安全头检查、证书分析和 ASN 查找。 | 社区实现, Go 开发 🏎️, 本地运行 🏠, 网络侦察 (httpx, asnmap)。                                     |
| [OpenCTI](https://github.com/Spathodea-Network/opencti-mcp)                      | 与 OpenCTI 平台交互，检索威胁情报数据（报告、指标、恶意软件等）。                                        | 社区实现, Python 开发, 威胁情报获取。                                                               |
| [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) | 强大的 MCP 服务器，审计 npm 包依赖项的安全漏洞。内置远程 npm 注册表集成，用于实时安全检查。                   | 社区实现, TypeScript 开发 📇, 云服务 ☁️, NPM 依赖安全审计。                                       |
| [rad-security/mcp-server](https://github.com/rad-security/mcp-server)              | RAD Security 的 MCP 服务器，为 Kubernetes 和云环境提供 AI 驱动的安全洞察。提供查询 Rad Security API 等工具。 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, K8s/云安全 (RAD Security)。                               |
| [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp)                  | 用于查询 CVE-Search API 的 MCP 服务器。提供全面访问 CVE-Search，浏览供应商/产品、按 ID 获取 CVE、获取最新 CVE。 | 社区实现, Python 开发 🐍, 本地运行 🏠, CVE 漏洞信息查询 (CVE-Search)。                              |
| [sapientpants/deepsource-mcp-server](https://github.com/sapientpants/deepsource-mcp-server) | 与 DeepSource 集成的 MCP 服务器，为 AI 助手提供代码质量指标、问题和质量门状态的访问。                    | 社区实现, TypeScript 开发 📇, 云端/本地 ☁️🏠, 代码质量 (DeepSource)。                             |
| [sapientpants/sonarqube-mcp-server](https://github.com/sapientpants/sonarqube-mcp-server) | 与 SonarQube 集成的 MCP 服务器，为 AI 助手提供代码质量指标、问题和质量门状态的访问。                   | 社区实现, Rust 开发 🦀, 云端/本地 ☁️🏠, 代码质量 (SonarQube)。                                   |
| [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp)        | 将流行的开源工具整合到单一 MCP 接口中的一体化安全测试工具箱。连接 AI 代理，实现渗透测试、漏洞赏金、威胁狩猎等任务。 | 社区实现, Python 开发 🐍, 本地运行 🏠, 安全测试工具箱。                                            |
| [Whois MCP](https://github.com/bharathvaj-ganesan/whois-mcp)                     | 对域名、IP、ASN 和 TLD 执行 whois 查询。                                                          | 社区实现, Python 开发, Whois 查询。                                                                |

---

### 🌍 地理位置与出行

*(让 AI 能够处理地理位置数据、地图、天气、交通出行信息等)*

| 名称                                                                               | 中文介绍                                                                                              | 备注                                                                                             |
| :--------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------- |
| [Airbnb MCP Server](https://github.com/openbnb-org/mcp-server-airbnb)              | 提供搜索 Airbnb 和获取房源详情的工具。                                                         | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Airbnb 搜索。                                         |
| [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) | 使用 IPInfo API 获取 IP 地址地理位置和网络信息。                                                 | 社区实现, Python 开发 🐍, 云服务 ☁️, IP 地址信息 (IPInfo)。                                   |
| [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) | 具有基于位置服务和地理空间数据的 OpenStreetMap MCP 服务器。                                  | 社区实现, Python 开发 🐍, 本地运行 🏠, OpenStreetMap 数据。                                   |
| [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp)          | 用于附近地点搜索的 MCP 服务器，带基于 IP 的位置检测。                                            | 社区实现, Python 开发 🐍, 云服务 ☁️, 附近地点搜索。                                             |
| [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) | 国家公园服务 API 集成，提供美国国家公园的公园详情、警报、游客中心、露营地和活动的最新信息。           | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 美国国家公园信息。                                 |
| [louiscklaw/hko-mcp](https://github.com/louiscklaw/hko-mcp)                      | 从香港天文台获取天气信息的基本演示 MCP 服务器。                                                  | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 香港天气。                                          |
| [modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) | Google Maps 集成，提供定位服务、路线规划和地点详情。                                                  | 官方参考, TypeScript 开发 📇, 云服务 ☁️, Google Maps 集成。                                 |
| [NS Travel Information MCP Server](https://github.com/r-huijts/ns-mcp-server)        | 访问荷兰铁路 (NS) 的旅行信息、时刻表和实时更新。                                                 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 荷兰铁路信息。                                         |
| [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp)             | 使 LLM 能与 Tripadvisor API 交互的 MCP 服务器，支持位置数据、评论和照片。                        | 社区实现, TypeScript/Python 开发 📇🐍, Tripadvisor API 集成。                                 |
| [QGIS MCP](https://github.com/jjsantos01/qgis_mcp)                               | 通过 MCP 将 QGIS Desktop 连接到 Claude AI。实现提示辅助的项目创建、图层加载、代码执行等。          | 社区实现, QGIS 集成。                                                                          |
| [SaintDoresh/Weather-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Weather-MCP-ClaudeDesktop.git) | 使用 OpenWeatherMap API 提供实时天气数据、预报和历史天气信息的 MCP 工具。                      | 社区实现, Python 开发 🐍, 云服务 ☁️, OpenWeatherMap 天气数据。                               |
| [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver)    | 访问任何时区的本地时间和获取当前本地时间。 (已在“其他”部分列出Time)                               | 社区实现, Python 开发 🐍, 本地运行 🏠, 时间/时区工具。                                          |
| [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo)                        | 用于 nominatim, ArcGIS, Bing 的地理编码 MCP 服务器。                                         | 社区实现, Python 开发 🐍, 本地运行 🏠, 地理编码服务。                                           |

---

### 🏃 体育与游戏

*(让 AI 能够访问体育赛事数据、游戏信息等)*

| 名称                                                                 | 中文介绍                                                                                                 | 备注                                                                                               |
| :------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------- |
| [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) | 用于 Unity3d 游戏引擎集成的 MCP 服务器，用于游戏开发。                                              | 社区实现, TypeScript/C# 开发 📇#️⃣, 本地运行 🏠, Unity3D 集成。                                  |
| [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp)    | 用于与 Godot 游戏引擎交互的 MCP 服务器，提供编辑、运行、调试和管理 Godot 项目中场景的工具。               | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Godot 引擎集成。                                     |
| [kw510/strava-mcp](https://github.com/kw510/strava-mcp)              | 用于 Strava (体育锻炼追踪应用) 的 MCP 服务器。                                                    | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Strava API 集成 (另一版本)。                            |
| [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) | 集成 balldontlie API，提供 NBA、NFL 和 MLB 的球员、球队和比赛信息。                               | 社区实现, TypeScript 开发 📇, 体育赛事数据 (balldontlie API)。                                  |
| [pab1ito/chess-mcp](https://github.com/pab1it0/chess-mcp)            | 访问 Chess.com 玩家数据、对局记录和其他公共信息，允许 AI 助手搜索和分析国际象棋信息。                 | 社区实现, Python 开发 🐍, 云服务 ☁️, Chess.com 数据。                                          |
| [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) | 通过自然语言访问自行车比赛数据、结果和统计信息。功能包括从 firstcycling.com 检索出发名单、比赛结果和车手信息。 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 自行车赛事数据 (firstcycling)。                     |
| [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp)        | 连接到 Strava API 的 MCP 服务器，提供通过 LLM 访问 Strava 数据的工具。                             | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Strava API 集成。                                      |
| [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp/) | 用于实时 Fantasy Premier League 数据和分析工具的 MCP 服务器。                                   | 社区实现, Python 开发 🐍, 云服务 ☁️, Fantasy Premier League (英超梦幻足球)。                 |
| [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp)        | 与 VRChat API 交互的 MCP 服务器。可获取好友、世界、虚拟形象等信息。 (已在通讯协作部分列出)              | 社区实现, TypeScript 开发 📇, 本地运行 🏠, VRChat API 交互。                                  |

---

### 🏛️ 艺术与文化

*(让 AI 能够访问艺术收藏、文化遗产、博物馆数据库等)*

| 名称                                                                   | 中文介绍                                                                                                   | 备注                                                                                        |
| :--------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------ |
| [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server)    | 通过官方 REST API v4 与 Quran.com 语料库交互的 MCP 服务器。                                            | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 古兰经文本交互。                                     |
| [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) | Rijksmuseum API 集成，用于艺术品搜索、详情和收藏。                                                    | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 荷兰国立博物馆艺术品。                               |
| [r-huijts/oorlogsbronnen-mcp](https://github.com/r-huijts/oorlogsbronnen-mcp) | Oorlogsbronnen (战争来源) API 集成，访问荷兰二战时期 (1940-1945) 的历史记录、照片和文件。                  | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 荷兰二战历史资料。                                 |
| [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp)          | 集成 AniList API 的 MCP 服务器，用于动漫和漫画信息。                                                  | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 动漫/漫画信息 (AniList)。                           |

---

### 🛠️ 其他实用工具与集成

*(包括计算器、API 集成、特定平台工具、聚合器、框架辅助等)*

| 名称                                                                               | 中文介绍                                                                                                     | 备注                                                                                                       |
| :--------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| [AgentRPC](https://github.com/agentrpc/agentrpc)                                 | AgentRPC 官方集成，跨网络边界连接任何语言的任何函数。                                                          | 官方实现 (AgentRPC), Go/Python/TS/Rust 开发 🏎️🐍📇🦀, 跨语言函数调用。                                    |
| [APIMatic MCP](https://github.com/apimatic/apimatic-validator-mcp)                 | APIMatic 官方集成，使用 APIMatic 验证 OpenAPI 规范。                                                         | 官方实现 (APIMatic), C# 开发 #️⃣, OpenAPI 规范验证。                                                   |
| [IBM wxflows](https://github.com/IBM/wxflows/tree/main/examples/mcp/javascript)    | IBM 官方工具平台，为任何数据源构建、测试和部署工具。                                                           | 官方实现 (IBM), JavaScript 开发, 通用工具平台。                                                          |
| [Langfuse Prompt Management](https://github.com/langfuse/mcp-server-langfuse)      | Langfuse 官方集成，用于协作编辑、版本控制、评估和发布提示的开源工具。(已在开发工具部分列出)                  | 官方实现 (Langfuse) 🎖️, Python 开发 🐍, 本地运行 🏠, Prompt 管理。                                     |
| [UnifAI](https://github.com/unifai-network/unifai-mcp-server)                    | UnifAI 官方集成，使用 UnifAI 网络动态搜索和调用工具。                                                        | 官方实现 (UnifAI), Go 开发, 动态工具发现与调用。                                                         |
| [VeyraX](https://github.com/VeyraX/veyrax-mcp)                                   | VeyraX 官方集成，单一工具控制 100+ API 集成和 UI 组件。                                                    | 官方实现 (VeyraX), Go 开发, 大规模 API/UI 控制。                                                         |
| [modelcontextprotocol/server-everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) | 展示 MCP 协议所有功能的 MCP 服务器。                                                                   | 官方参考, TypeScript 开发 📇, 本地运行 🏠, MCP 协议功能演示。                                            |
| [Calculator](https://github.com/githejie/mcp-server-calculator)                  | 使 LLM 能够使用计算器进行精确的数值计算。                                                                    | 社区实现, Python 开发 🐍, 本地运行 🏠, 基础计算器功能。                                                 |
| [Time](https://github.com/modelcontextprotocol/servers/tree/main/src/time)         | 官方参考实现，提供时间和时区转换能力。                                                                       | 官方参考, TypeScript 开发, 时间/时区工具。                                                               |
| [Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking) | 官方参考实现，通过思考序列进行动态和反思性问题解决。                                                           | 官方参考, TypeScript 开发, 复杂问题解决框架。                                                              |
| [OpenAPI AnyApi](https://github.com/baryhuang/mcp-server-any-openapi)            | 使用内置语义搜索与大型 OpenAPI 文档交互，可自定义前缀。                                                        | 社区实现, Python 开发, 大型 OpenAPI 交互。                                                               |
| [OpenAPI Schema](https://github.com/hannesj/mcp-openapi-schema)                  | 让 LLM 在不增加上下文的情况下探索大型 OpenAPI 模式。                                                         | 社区实现, TypeScript 开发, 大型 OpenAPI 模式探索。                                                         |
| [GraphQL Schema](https://github.com/hannesj/mcp-graphql-schema)                  | 让 LLM 在不增加上下文的情况下探索大型 GraphQL 模式。                                                         | 社区实现, TypeScript 开发, 大型 GraphQL 模式探索。                                                      |
| [julien040/anyquery](https://github.com/julien040/anyquery)                        | 通过 SQL 查询 40+ 应用，并连接 PG/MySQL/SQLite 数据库。本地优先，注重隐私。                          | 社区实现, Go 开发 🏎️, 本地/云端 🏠☁️, 多应用/数据库查询聚合器。                                           |
| [MetaMCP](https://github.com/metatool-ai/metatool-app)                           | MetaMCP 是统一的中间件 MCP 服务器，通过 GUI 管理您的 MCP 连接。                                       | 社区实现, TypeScript 开发 📇, 云端/本地 ☁️🏠, 跨平台 🍎🪟🐧, MCP 连接管理 GUI。                     |
| [OpenMCP](https://github.com/wegotdocs/open-mcp)                                 | 10 秒内将 Web API 转换为 MCP 服务器，并将其添加到开源注册表 [open-mcp.org](https://open-mcp.org)。 | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 跨平台 🍎🪟🐧, Web API 转 MCP 服务器。                   |
| [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) | 将多个 MCP 服务器组合到单个接口的综合代理服务器，具有广泛可见性功能 (工具/提示/资源/模板发现管理，调试平台)。 | 社区实现, TypeScript 开发 📇, 本地运行 🏠, MCP 代理与管理。                                           |
| [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp)              | 使 AI 模型能与比特币交互的 MCP 服务器 (生成密钥/验证地址/解码交易/查询区块链等)。                      | 社区实现, 比特币交互 ₿.                                                                                   |
| [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) | 通过工具或预定义提示使用 MCP 协议向 OpenAI, MistralAI, Anthropic, xAI, Google AI 或 DeepSeek 发送请求。 | 社区实现, Python/TypeScript 开发 🐍📇, 云服务 ☁️, 多 LLM API 调用。                                     |
| [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer)          | 为您安装其他 MCP 服务器的 MCP 服务器。                                                               | 社区实现, Python 开发 🐍, 本地运行 🏠, MCP 服务器安装器。                                               |
| [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) | 与 OpenAI Assistants 对话的 MCP (Claude 可以使用任何 GPT 模型作为其助手)。                             | 社区实现, Python 开发 🐍, 云服务 ☁️, 调用 OpenAI Assistants。                                         |
| [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) | 允许检查客户端机器本地时间或从 NTP 服务器获取当前 UTC 时间的 MCP 服务器。                               | 社区实现, Python 开发 🐍, 本地/云端 🏠☁️, 时间获取 (本地/NTP)。                                         |
| [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link)    | 无缝集成任何带有 OpenAPI Schema 的 API 与 AI Agents。                                                | 社区实现, Go 开发 🏎️, 本地运行 🏠, OpenAPI API 集成。                                                 |
| [baba786/phabricator-mcp-server](https://github.com/baba786/phabricator-mcp-server) | 与 Phabricator API 交互。                                                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, Phabricator 集成。                                                |
| [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) | 让 Claude 与 ChatGPT 对话并使用其网页搜索能力的 MCP 服务器。                                         | 社区实现, Python 开发 🐍, 云服务 ☁️, Claude 调用 ChatGPT (含搜索)。                                   |
| [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql)                  | 允许 AI 查询 GraphQL 服务器。                                                                    | 社区实现, TypeScript 开发 📇, 云服务 ☁️, GraphQL 查询。                                              |
| [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli)                      | 用于测试 MCP 服务器的另一个 CLI 工具。                                                               | 社区实现, Python 开发 🐍, 本地运行 🏠, MCP 测试 CLI。                                                |
| [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace)                  | 直接从 Claude 使用 HuggingFace Spaces。使用开源图像生成、聊天、视觉任务等。支持图像、音频和文本上传/下载。  | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Hugging Face Spaces 调用。                               |
| [future-audiences/wikimedia-enterprise-model-context-protocol](https://gitlab.wikimedia.org/repos/future-audiences/wikimedia-enterprise-model-context-protocol) | Wikipedia 文章查找 API。                                                                           | 社区实现 (Wikimedia), Python 开发 🐍, 云服务 ☁️, Wikipedia 文章查找。                               |
| [gotoolkits/DifyWorkflow](https://github.com/gotoolkits/mcp-difyworkflow-server)     | 用于查询和执行 Dify 工作流的工具。                                                                 | 社区实现, Go 开发 🏎️, 云服务 ☁️, Dify 工作流执行。                                                   |
| [jagan-shanmugam/climatiq-mcp-server](https://github.com/jagan-shanmugam/climatiq-mcp-server) | 用于访问 Climatiq API 计算碳排放的 MCP 服务器。使 AI 助手能执行实时碳计算并提供气候影响见解。             | 社区实现, Python 开发 🐍, 本地运行 🏠, 碳排放计算 (Climatiq API)。                                  |
| [joshuarileydev/mac-apps-launcher-mcp-server](https://github.com/JoshuaRileyDev/mac-apps-launcher) | 在 macOS 上列出和启动应用程序的 MCP 服务器。                                                        | 社区实现, TypeScript 开发 📇, 本地运行 🏠, macOS 应用启动器 🍎。                                    |
| [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq)    | 启用与 RabbitMQ 的交互（管理操作、消息入队/出队）。                                                   | 社区实现, Python 开发 🐍, 本地运行 🏠, RabbitMQ 交互。                                              |
| [kukapay/whattimeisit-mcp](https://github.com/kukapay/whattimeisit-mcp)          | 精确告知当前时间的轻量级 MCP 服务器。                                                              | 社区实现, Python 开发 🐍, 云服务 ☁️, 时间工具。                                                     |
| [kukapay/whereami-mcp](https://github.com/kukapay/whereami-mcp)                | 基于当前 IP 精确告知您所在位置的轻量级 MCP 服务器。                                                   | 社区实现, Python 开发 🐍, 云服务 ☁️, IP 定位。                                                     |
| [kukapay/whoami-mcp](https://github.com/kukapay/whoami-mcp)                    | 精确告知您是谁的轻量级 MCP 服务器。(可能指用户信息?)                                                  | 社区实现, Python 开发 🐍, 本地运行 🏠, 用户信息(?)。                                                  |
| [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) | 中间件服务器，使同一 MCP 服务器的多个隔离实例能以独特的命名空间和配置独立共存。                        | 社区实现, TypeScript 开发 📇, 本地运行 🏠, MCP 服务器多实例管理。                                 |
| [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway)          | MCP SSE 服务器的网关演示。                                                                        | 社区实现, TypeScript 开发 📇, MCP SSE 网关示例。                                                    |
| [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy)        | 通过 Giphy API 从 Giphy 的庞大库中搜索和检索 GIF。                                                 | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Giphy GIF 搜索。                                          |
| [marcelmarais/Spotify](https://github.com/marcelmarais/spotify-mcp-server)      | 控制 Spotify 播放和管理播放列表。                                                                 | 社区实现, TypeScript 开发 📇, 本地运行 🏠, Spotify 控制。                                            |
| [mcp-server-jfx](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jfx) | 在 JavaFX 画布上绘图。                                                                            | 社区实现 (Quarkiverse), Java 开发 ☕, 本地运行 🏠, JavaFX 绘图。                                  |
| [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe)              | 本地优先系统，捕获屏幕/音频并带时间戳索引，SQL/嵌入存储，语义搜索，LLM 历史分析，事件触发动作。通过 NextJS 插件生态系统构建上下文感知 AI 代理。 | 官方实现 (mediar.ai) 🎖️, Rust 开发 🦀, 本地运行 🏠, macOS 🍎, 屏幕/音频捕获与分析 RAG。        |
| [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp)      | 简单的 MCP 服务器，在 Cline 和 Cursor 等工具中启用人机回圈工作流。                                     | 社区实现, Python 开发 🐍, 本地运行 🏠, 人机回圈反馈。                                              |
| [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp)                  | Token 高效的 Go 文档服务器，为 AI 助手提供对包文档和类型的智能访问，无需读取整个源文件。                  | 社区实现, Go 开发 🏎️, 本地运行 🏠, Go 文档智能访问。                                              |
| [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai)                      | 与 OpenAI 最智能的模型聊天。                                                                       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 调用 OpenAI 模型。                                       |
| [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui.git)      | 可以执行键盘输入和鼠标移动等命令的 MCP 服务器。                                                        | 社区实现, 本地运行 🏠, macOS 🍎, GUI 自动化 (Swift)。                                            |
| [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) | 面向开发者的有用工具集合，几乎包含工程师所需的一切：Confluence, Jira, Youtube, 运行脚本, 知识库 RAG, Fetch URL, 管理 Youtube 频道, 邮件, 日历, Gitlab。 | 社区实现, Go 开发 🏎️, 本地运行 🏠, 开发者工具集。                                                |
| [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) | 屏幕 GUI 的自动操作。                                                                            | 社区实现, Python 开发 🐍, GUI 自动化。                                                              |
| [Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools) | Open Strategy Partners 的一套营销工具，包括写作风格、编辑规范和产品营销价值图创建。                   | 社区实现, Python 开发 🐍, 本地运行 🏠, 营销工具套件。                                             |
| [paulotaylor/voyp-mcp](https://github.com/paulotaylor/voyp-mcp)                | VOYP - Voice Over Your Phone MCP 服务器，用于拨打电话。                                            | 社区实现, TypeScript 开发 📇, 电话拨打。                                                          |
| [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) | 直接从 Claude 使用 MCP 协议查询 OpenAI 模型。                                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, Claude 调用 OpenAI。                                         |
| [pskill9/hn-server](https://github.com/pskill9/hn-server)                      | 解析 news.ycombinator.com (Hacker News) 的 HTML 内容，并为不同类型的故事提供结构化数据。               | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Hacker News 内容解析。                                   |
| [pskill9/website-downloader](https://github.com/pskill9/website-downloader)      | 使用 wget 下载整个网站的 MCP 服务器。保留网站结构并将链接转换为本地工作。                               | 社区实现, Go 开发 🚀, 网站下载器 (wget)。                                                        |
| [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server)    | 通过调用 "Vibe-check" Agent 来确保用户对齐，防止级联错误和范围蔓延的 MCP 服务器。                     | 社区实现, TypeScript 开发 📇, 云服务 ☁️, Agent 对齐检查。                                        |
| [pwh-pwh/cal-mcp](https://github.com/pwh-pwh/cal-mcp)                          | 用于数学表达式计算的 MCP 服务器。                                                                    | 社区实现, 数学计算。                                                                                |
| [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) | 与任何其他 OpenAI SDK 兼容的聊天完成 API 聊天，如 Perplexity, Groq, xAI 等。                       | 社区实现, 任意 OpenAI 兼容 API 调用。                                                              |
| [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp)                | 允许 AI 读取 .ged 文件和遗传数据。                                                               | 社区实现, Python 开发 🐍, 本地运行 🏠, 家族史/遗传数据读取 (.ged)。                               |
| [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw/blob/main/src/wcgw/client/mcp_server/Readme.md) | 自主 Shell 执行、计算机控制和编码代理 (Mac)。                                                       | 社区实现, Python 开发 🐍, 本地运行 🏠, macOS 🍎, 自主控制/编码代理。                           |
| [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) | 用于查询 Wolfram Alpha API 的 MCP 服务器。                                                        | 社区实现, Python 开发 🐍, 云服务 ☁️, Wolfram Alpha 查询。                                         |
| [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp)                    | 与 TikTok 视频交互。                                                                             | 社区实现, TypeScript 开发 📇, 云服务 ☁️, TikTok 交互。                                           |
| [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server)    | 用于 Oura (睡眠追踪应用) 的 MCP 服务器。                                                           | 社区实现, Python 开发 🐍, 云服务 ☁️, Oura 睡眠数据。                                                |
| [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku)                        | Wanaku MCP 路由器是基于 SSE 的 MCP 服务器，提供可扩展的路由引擎，允许将企业系统与 AI Agents 集成。           | 官方实现 (Wanaku AI), 云端/本地 🏠☁️, MCP 路由引擎。                                               |
| [wong2/mcp-cli](https://github.com/wong2/mcp-cli)                          | 用于测试 MCP 服务器的 CLI 工具 (另一版本)。                                                         | 社区实现, TypeScript 开发 📇, 本地运行 🏠, MCP 测试 CLI (TS)。                                     |
| [ws-mcp](https://github.com/nick1udwig/ws-mcp)                            | 用 WebSocket 包装 MCP 服务器 (用于 [kitbitz](https://github.com/nick1udwig/kibitz))。         | 社区实现, WebSocket 包装器。                                                                        |
| [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime)            | 提供各种格式的日期和时间功能的 MCP 服务器。                                                          | 社区实现, 日期时间工具。                                                                            |
| [zueai/mcp-manager](https://github.com/zueai/mcp-manager)                    | 用于安装和管理 Claude Desktop App 的 MCP 服务器的简单 Web UI。                                      | 社区实现, TypeScript 开发 📇, 云服务 ☁️, MCP 服务器管理 Web UI。                                     |
| [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server)  | 用于集成语雀 API 的 MCP 服务器，允许 AI 模型管理文档、与知识库交互、搜索内容和访问语雀平台的分析数据。       | 社区实现, TypeScript 开发 📇, 云服务 ☁️, 语雀 API 集成。                                         |
| [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) | 通过在 MCP 循环中直接添加本地用户提示和聊天功能，实现交互式 LLM 工作流。 | 社区实现, TypeScript 开发 📇, 本地运行 🏠, 人机交互工作流。 |

---

### 更多 MCP Server 资源

* [MCP.so](https://mcp.so/) 收录了近 8000 MCP Servers

![](https://files.mdnice.com/user/43439/4f1c6e0d-f1b3-423c-b069-fa2c502d8557.png)

* [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
* [web目录](https://glama.ai/mcp/servers)。
* [MCP.ing](https://mcp.ing) 一个资源丰富的 MCP Server库。

![mcp ing](https://youjb.com/images/2025/04/25/mcp-ingb03704c206230a97.png)


## MCP 更多玩法

* [mcp-agent](https://github.com/lastmile-ai/mcp-agent): Build effective agents using Model Context Protocol and simple workflow patterns
* [mcsmcp](https://github.com/microsoft/mcsmcp) Lab for creating an MCP Server and using it in Microsoft Copilot Studio.
* [mindsdb](https://github.com/mindsdb/mindsdb) AI's query engine - Platform for building AI that can answer questions over large scale federated data. - The only MCP Server you'll ever need

### 亲测优质Server

发现很多server 可用性不够，单开一个模块推荐自己使用过的优质 Server，欢迎大家在这个板块提交自己测试后的优质Server，提交的时候请同步提交使用 Server截图。

* [notion-mcp-server](https://github.com/makenotion/notion-mcp-server) Official Notion MCP Server
* [douyin-mcp-server](https://github.com/yzfly/douyin-mcp-server) 提取抖音无水印视频链接，视频文案
* [mcp-hotnews-server](https://github.com/wopal-cn/mcp-hotnews-server) A Model Context Protocol server that provides real-time hot trending topics from major Chinese social platforms and news sites.
* [mcp-github-trending](https://github.com/hetaoBackend/mcp-github-trending) MCP server for getting github trending repos & developers


## MCP 资源

想玩转 MCP？这些资源帮你省时间：

- **官方文档**  
  - [MCP 官网](https://www.claudemcp.com/)  
  - [Anthropic MCP 介绍](https://www.anthropic.com/news/model-context-protocol)  


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

---

## 许可证

本项目基于 MIT 许可证，自由使用和修改，请保留版权声明。  
Copyright (c) 2025 Awesome-MCP-ZH Contributors

---
