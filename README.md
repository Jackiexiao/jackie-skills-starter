# 🚀 一行命令，装好你的 AI Skills 懒人包（开发 / 营销 / 创作 / 日常）

不想研究一堆概念？就想**马上能用**？
这套就是给你的：按场景分成 4 大类，选一类，**一键安装**，直接开工。

---

## 30 秒快速开始

### 1) 先选你的场景

- **Dev（开发）**：写功能、调试、测试、评审、交付
- **Marketing（营销）**：SEO、文案、转化、定价、埋点
- **Creator（创作）**：选题、文案、视觉、视频
- **Everyday（日常）**：PDF/Word/Excel/PPT、网页自动化、效率流程

### 2) 复制一条命令安装

```bash
npx skills add Jackiexiao/jackie-skills-dev --all
npx skills add Jackiexiao/jackie-skills-marketing --all
npx skills add Jackiexiao/jackie-skills-creator --all
npx skills add Jackiexiao/jackie-skills-everyday --all
```

> 适用于几乎所有主流 AI 编程工具：**Claude Code / Codex / Trae / OpenClaw** 等。

### 3) 马上用起来（通用模板）

安装后，直接在你的 AI 工具里这样说：

- `用 <skill-name> 帮我完成 <任务目标>，给我可直接执行的结果。`

例如：

- `用 webapp-testing 帮我测试“注册→登录→下单”流程，输出失败点和修复建议。`
- `用 copywriting 重写这个落地页首屏，目标是提升注册转化。`

---

## 安装后怎么管理（必备）

### 查看已安装 skills

```bash
npx skills ls
```

### 删除某个 skill

```bash
npx skills remove <skill-name>
```

例如：

```bash
npx skills remove webapp-testing
```

---

## 4 大类别总览（共 49 个）

## 1) Dev（14）

仓库：<https://github.com/Jackiexiao/jackie-skills-dev>

| Skill | 一句话怎么用 | 示例 |
|---|---|---|
| `frontend-design` | 快速生成高质量页面与组件 | 做一个 SaaS 定价页，深色风格、移动端优先 |
| `vercel-react-best-practices` | React 性能与结构优化 | 重构列表页，减少重复渲染 |
| `next-best-practices` | Next.js 路由与渲染边界优化 | 拆分 Server/Client 组件 |
| `vercel-composition-patterns` | 组件组合模式设计 | 把大组件改成 compound components |
| `supabase-postgres-best-practices` | 数据库查询与索引优化 | 为慢查询设计索引策略 |
| `systematic-debugging` | 系统化定位 bug 根因 | 接口偶发 500，先定位再修复 |
| `test-driven-development` | 先测后写降低回归 | 先写失败测试再实现功能 |
| `webapp-testing` | 自动化测试网页流程 | 跑登录到支付全链路测试 |
| `requesting-code-review` | 发起高质量评审请求 | 输出 PR 风险点+测试范围 |
| `receiving-code-review` | 评审意见分析与落地 | 判断哪些建议该改 |
| `verification-before-completion` | 完成前做证据化验证 | 出一份上线前验证清单 |
| `using-git-worktrees` | 并行任务隔离开发环境 | 为 bug 创建独立 worktree |
| `subagent-driven-development` | 复杂任务并行拆解执行 | 拆分“支付重构”子任务 |
| `mcp-builder` | 构建 MCP 工具连接外部系统 | 把 CRM API 封成 MCP server |

## 2) Marketing（14）

仓库：<https://github.com/Jackiexiao/jackie-skills-marketing>

| Skill | 一句话怎么用 | 示例 |
|---|---|---|
| `audit-website` | 网站体检并给优化优先级 | 输出 TOP10 修复项 |
| `seo-audit` | SEO 问题诊断 | 分析页面不排名原因 |
| `programmatic-seo` | 批量 SEO 页面策略 | 设计“城市+行业”模板 |
| `copywriting` | 产出转化导向文案 | 重写首页首屏+CTA |
| `copy-editing` | 文案润色提效 | 缩短文案并增强行动感 |
| `content-strategy` | 内容计划与节奏管理 | 生成 30 天选题日历 |
| `marketing-ideas` | 增长点子快速生成 | 给 20 个低预算增长动作 |
| `marketing-psychology` | 心理学驱动转化优化 | 重写价格页触发机制 |
| `product-marketing-context` | 统一定位与卖点表达 | 梳理人群、痛点、差异化 |
| `pricing-strategy` | 定价与套餐设计 | 设计三档 SaaS 套餐 |
| `page-cro` | 页面转化率优化 | 给 5 个可 A/B 的改动 |
| `launch-strategy` | 新功能发布节奏 | 设计 14 天发布计划 |
| `analytics-tracking` | 埋点与漏斗设计 | 搭建注册→付费追踪 |
| `schema-markup` | 增强结构化数据展示 | 生成 JSON-LD schema |

## 3) Creator（9）

仓库：<https://github.com/Jackiexiao/jackie-skills-creator>

| Skill | 一句话怎么用 | 示例 |
|---|---|---|
| `social-content` | 按平台生成内容版本 | 同题输出小红书/X/公众号 |
| `copywriting` | 提升标题与开头吸引力 | 写 10 个高点击标题 |
| `copy-editing` | 优化口语感和可读性 | 润色口播稿更自然 |
| `canvas-design` | 快速做海报/封面图 | 做“AI 提效清单”封面 |
| `remotion-best-practices` | 视频脚本与动画结构化 | 设计 60 秒产品动画分镜 |
| `ui-ux-pro-max` | 提升视觉与交互质感 | 优化个人主页层次 |
| `algorithmic-art` | 生成独特创意视觉 | 生成统一风格背景图 |
| `web-design-guidelines` | 去掉“廉价 AI 感” | 审查页面视觉并修正 |
| `tailwind-design-system` | 搭建 Tailwind 设计系统 | 统一按钮/卡片/表单规范 |

## 4) Everyday（12）

仓库：<https://github.com/Jackiexiao/jackie-skills-everyday>

| Skill | 一句话怎么用 | 示例 |
|---|---|---|
| `pdf` | PDF 读取/合并/拆分/OCR | 合并 3 份合同并提取目录 |
| `docx` | Word 文档生成与编辑 | 把会议纪要整理成周报 |
| `xlsx` | 表格清洗与报表分析 | 按地区汇总销售并画图 |
| `pptx` | 快速生成演示文稿 | 生成 10 页项目汇报大纲 |
| `agent-browser` | 浏览器自动执行任务 | 登录网站并抓取订单列表 |
| `browser-use` | 通用网页交互自动化 | 自动填表并截图留档 |
| `writing-plans` | 多步骤任务拆解 | 生成 2 周搬家执行计划 |
| `brainstorming` | 快速发散思路 | 给 30 个副业方向并分组 |
| `find-skills` | 按需求找对应 skill | 想做播客剪辑该装哪些 |
| `using-superpowers` | 固化高效工作流 | 建立“分析→执行→验证”流程 |
| `executing-plans` | 按计划稳定推进 | 把方案拆成今天前 5 步 |
| `skill-creator` | 把经验封成可复用 skill | 把日报流程做成 skill |

---

## 最后一句

你不需要一次学会所有技能。
**先选一个分类，一键装上，跑通一个真实任务**，这就是最快的升级路径。