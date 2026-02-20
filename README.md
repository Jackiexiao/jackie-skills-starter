# Jackie Skills Starter

一键装好你的 AI 技能栈：开发 / 营销 / 自媒体 / 日常效率（4 套精选）

---

## 短版（30 秒看完）

Skills 最大的问题通常不是“装不上”，而是“先装哪套最值”。
我把高频、实用、装完就能开工的能力，整理成 4 个按场景划分的仓库：

- **Dev（开发）**：把“写功能 + 调试 + 测试 + 评审”这一整套流程跑顺
- **Marketing（营销）**：从文案、SEO、转化到埋点，覆盖增长闭环
- **Creator（自媒体）**：内容表达 + 视觉产出 + 视频制作，一次配齐
- **Everyday（日常效率）**：PDF/Word/Excel/PPT + 浏览器自动化，办公即插即用

核心原则：**精选，不贪多；装完就能用。**

一键安装（按需选一套或多套）：

```bash
npx skills add Jackiexiao/jackie-skills-dev --all
npx skills add Jackiexiao/jackie-skills-marketing --all
npx skills add Jackiexiao/jackie-skills-creator --all
npx skills add Jackiexiao/jackie-skills-everyday --all
```

---

## 长版（完整说明）

### 为什么做这 4 套？

你不需要 100 个“看起来很强”的 skill。
你需要的是：今天就能解决问题的那几组能力。

所以这 4 套的设计不是“收集癖”，而是“**场景优先**”：

- 避免在海量 skill 里反复试错
- 降低第一次使用的决策成本
- 让团队/个人能快速形成稳定工作流

---

### 4 套仓库入口

- Dev: <https://github.com/Jackiexiao/jackie-skills-dev>
- Marketing: <https://github.com/Jackiexiao/jackie-skills-marketing>
- Creator: <https://github.com/Jackiexiao/jackie-skills-creator>
- Everyday: <https://github.com/Jackiexiao/jackie-skills-everyday>

---

### 你该先装哪套？

- 你主要写代码、做产品：先装 **Dev**
- 你主要做增长、获客、转化：先装 **Marketing**
- 你要持续做内容输出：先装 **Creator**
- 你要快速提升办公效率：先装 **Everyday**

组合建议：

- 独立开发者：**Dev + Marketing**
- 技术博主/产品博主：**Dev + Creator**
- 小团队通用默认：**Everyday + Dev**

---

### 补充推荐（你给的清单里，之前未明确放入“推荐位”的）

下面这些值得补上，我已放进主推荐说明：

1. **`skill-creator`**（Anthropic 官方）
   - 适合“自己做/改 skill”的用户，是从使用者走向构建者的关键能力。
2. **`using-superpowers`**（superpowers 组合）
   - 用于会话起手的流程编排，能显著降低漏步骤和流程混乱。
3. **`humanizer-zh`**（去 AI 味）
   - 适合内容发布前的人味润色，尤其是中文社媒、博客、营销文案。
4. **`vercel-labs/skills` 里的专项能力**
   - 适合需要补强 Vercel 生态（尤其 AI 产品方向）的人群按需扩展。

你列出的这些已在推荐体系中（或对应套装里）：

- `pptx` / `pdf` / `docx` / `xlsx`
- `ui-ux-pro-max`
- `agent-browser`
- `remotion-best-practices`

---

### 直接可用的补充安装命令

```bash
# Anthropic 官方 skills（可按需挑）
npx skills add https://github.com/anthropics/skills --skill skill-creator

# UI/UX 强化
npx skills add https://github.com/nextlevelbuilder/ui-ux-pro-max-skill --skill ui-ux-pro-max

# Superpowers（14 个 skill 组合）
npx skills add https://github.com/obra/superpowers

# 去 AI 味（中文）
npx skills add https://github.com/op7418/humanizer-zh --skill humanizer-zh

# Vercel skills 集合
npx skills add https://github.com/vercel-labs/skills

# 浏览器自动化（Vercel）
npx skills add https://github.com/vercel-labs/agent-browser --skill agent-browser

# AI 产品介绍动画（Remotion）
npx skills add https://github.com/remotion-dev/skills --skill remotion-best-practices
```

---

### 最后一句

如果你只做一件事：**先装一套，再真实用 3 天。**
能持续帮你省时间、提质量的，才是“该长期保留”的技能栈。