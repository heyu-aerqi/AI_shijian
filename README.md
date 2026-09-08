# AI_shijian

个人 AI 工具实践项目集合。

---

## 📦 项目列表

### 1. AGENTHOT — Agent 行业动态聚合

> Agent 行业动态聚合 · 每日精选与深度分析。发现国内外 AI Agent 产品，获取行业动态、开发技巧和开源项目。

**文件**：`agenthot.zip`（191KB）

#### 简介

AGENTHOT 是一个基于 Next.js 16 构建的 AI Agent 行业动态聚合平台，实时抓取 16 个 RSS / HTML / API 数据源，自动分类、评分、去重，为开发者提供一站式的 Agent 领域资讯浏览体验。

#### 6 大 Tab 页

| Tab | 说明 |
|-----|------|
| **全部** | 所有动态汇总，按热度排序 |
| **模型** | AI 模型发布动态（OpenAI / Google / Anthropic / Hugging Face 等） |
| **产品** | Agent 产品发现，16 款精选产品 + AI 产品分析 |
| **行业** | 行业新闻、融资动态、政策法规 |
| **技巧** | 开发教程、架构设计、MCP 工具推荐 |
| **博客** | Agent 开源项目（14 个 GitHub 仓库，实时 star 数） |

#### 16 个数据源

| 数据源 | 类型 | 分类 |
|--------|------|------|
| OpenAI | RSS | 模型 |
| Google AI | RSS | 模型 |
| Google Blog | RSS | 模型 |
| Hugging Face | RSS | 模型 |
| Anthropic | HTML 抓取 | 模型 |
| 量子位 | RSS | 行业 |
| 雷锋网 | RSS | 行业 |
| LangChain | RSS | 技巧 |
| Simon Willison | RSS | 技巧 |
| Lil'Log | RSS | 技巧 |
| AWS ML | RSS | 技巧 |
| Cloudflare | RSS | 技巧 |
| Hacker News | API + 关键词过滤 | 技巧 |
| MCP AIbase | HTML 抓取（60+ MCP server） | 技巧 |
| AIHOT 精选 | REST API | 行业 |
| GitHub 开源项目 | GitHub API | 博客 |

#### 核心能力

- **实时聚合**：并行抓取 16 个数据源，10 分钟缓存，支持手动刷新
- **自动分类**：基于关键词匹配 + 源权重的自动分类算法
- **热度评分**：综合源权重、时效性、Agent 关键词匹配度的 0-100 评分
- **去重**：按 URL 去重，同 URL 保留高分条目
- **搜索**：全文本搜索（标题、摘要、标签）
- **详情页**：每条动态有独立详情页，包含推荐理由、AI 摘要、正文
- **深色/浅色/系统** 三种主题切换
- **响应式设计**：桌面 + 移动端适配

#### 技术栈

| 技术 | 版本 | 用途 |
|------|------|------|
| Next.js | 16.2.11 | 全栈框架（App Router） |
| React | 19.2.4 | UI 库 |
| TypeScript | ^5 | 类型安全 |
| Tailwind CSS | ^4 | 样式 |
| shadcn/ui | ^4.14 | UI 组件库 |
| SWR | ^2.4.2 | 数据请求 + 缓存 |
| rss-parser | ^3.13 | RSS 解析 |
| next-themes | ^0.4.6 | 主题切换 |
| lucide-react | ^1.26 | 图标 |

#### 快速开始

1. 解压 `agenthot.zip`
2. **macOS**：双击 `start.command` 启动
3. **Windows**：双击 `start.bat` 启动
4. 首次运行会自动安装依赖（需已安装 [Node.js](https://nodejs.org/) ≥ 20）
5. 浏览器自动打开 http://localhost:3000

> 也可以命令行启动：`npm install && npm run dev`

---

### 2. AI 小工具

**文件**：`AI小工具.zip`（3.4MB）

个人 AI 工具集合。
