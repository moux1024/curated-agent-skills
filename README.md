# Curated Agent Skills（与本地会话内容相关）

整理自 https://github.com/topics/agent-skills（2026-11-06），筛选标准：与本地工作流相关——儿童计算机架构教育游戏（Unity3D）开发、中文长文写作、小红书/推广内容、可视化图解、跨会话改进。

## 开发工程（与 Unity3D 教育游戏开发相关）

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [morluto/rea](https://github.com/morluto/rea) | 434k | 2026-11-06 | 用 agent 逆向工程任何东西（应用行为到原生二进制）— 2026-11-06 新增，可为"理解模块行为"教学设计提供参照 |
| [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 185k | 2026-10-29 | 让 agent 像"最懒的资深工程师"一样思考：能不写的代码就不写（YAGNI），适合克制地推进游戏原型 |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 114k | 2026-11-01 | 生产级工程 skill 集，覆盖编码 agent 的核心开发流程 |
| [alibaba/open-code-review](https://github.com/alibaba/open-code-review) | 49.5k | 2026-11-05 | 确定性流水线 + LLM Agent 的混合代码审查，内置多语言规则集（NPE/线程安全/XSS/SQL注入）— 2026-11-05 新增 |

## 写作与去模板化

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [blader/humanizer](https://github.com/blader/humanizer) | 65.3k | 2026-10-28 | 去除 AI 生成痕迹的写作 skill。本地已有其中文定制版 `humanizer-zh`，仅作上游参考 |

## 营销与内容增长

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 58.7k | 2026-11-04 | CRO、文案、SEO、增长工程，与小红书推广工作流相关 |

## 设计与反 AI slop

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | 106k | 2026-11-06 | 协作式 AI 设计 agent 工作区（本地优先），可为游戏 UI/原型设计提供参照 — 2026-11-06 新增（注：工作区应用，非 skill） |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 111k | 2026-11-05 | 给编码 agent 设计品味：艺术方向、参考图、浏览器检查 |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 104k | 2026-11-05 | 设计词汇表，polish/critique/audit，拦截 AI slop |

## 可视化与图解（与游戏架构讲解图相关）

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | 93.9k | 2026-11-06 | 把想法/计划/代码库变成交互式图表——与"计算机架构教育"的图解需求直接相关 |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 65.3k | 2026-11-03 | 编辑级图表设计，45 种图型，自包含 HTML+SVG |

## 跨会话自我改进

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [pskoett/self-improving-agent](https://github.com/pskoett/self-improving-agent) | 790 | 2026-10-22 | 跨会话沉淀 learnings/errors/corrections，持续优化历史会话效果。**已安装到本地 v4.0.5；2026-11-06 复查上游无更新** |

## 综合索引

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [anthropics/skills](https://github.com/anthropics/skills) | 188k | 2026-10-28 | Anthropic 官方 Agent Skills 仓库 |
| [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) | 57.3k | 2026-11-06 | Claude Code 优质资源精选（skills/plugins/工具）— 2026-11-05 新增 |
| [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) | 49.2k | 2026-11-05 | 2,884+ 可复用 agent skill，含本地目录发现与计划预览 |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 53.6k | 2026-10-30 | 5,400+ 已筛选分类的 OpenClaw skill 索引 |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 78.9k | 2026-09-18 | Claude Skills 精选列表 |

### 2026-11-06 浏览后过滤未收录

- paperclipai/paperclip（111k，工作 agent 管理应用）、CherryHQ/cherry-studio（53k，模型工作区应用）：均非 skill
- career-ops-hq/career-ops（80k，求职 agent）：与本地工作流无关
- K-Dense-AI/scientific-agent-skills（56k，科学技能库）：与本地工作流无关

---
*由 WorkBuddy 自动化整理生成，数据截取自 2026-11-06 的 GitHub 话题页。*

## 已基于本清单反向优化自建 skill（2026-11-02）

| 自建 skill | 参照来源 | 改动 |
|------------|---------|------|
| humanizer-zh v2.1.0 | blader/humanizer v3.1.0 | 同步两条总规则、结构/词表严重度分级、幸存模式复查步（1/2/6/8/19）、词表衰减说明；description 加触发推力 |
| longform v0.1.1 | anthropics/skills 官方规范 | 修复死指针（xhs-replica）、专家包引用加降级说明、description 触发推力 |
| xhs-story v1.1.1 | marketingskills/copywriting | Step 5 注入三问门（画面化/可证伪/竞品换位）、punch 配给、[NEED] 缺料标记 |
| promo-atlas v1.0.2 | marketingskills/copywriting | copy-voice.md 新增换位测试与 punch 配额，接入交付前六问 |
| novel-atlas v0.5.0 | — | 审计通过：渐进披露、copy 复查、references 均达标，无需改动 |

## Skill 审查记录

- 2026-11-06：会话存档访问第 4 次被权限拒绝，沿用 2026-11-02 调用统计（grill-me 7、novel-atlas 3、xhs-story 1、promo-atlas 1、humanizer-zh 0、longform 0）。无删除项：humanizer-zh/longform 受用户级 MEMORY.md 保护，其余均在近期有调用。topic 页新增 6 仓库，其中 morluto/rea、nexu-io/open-design 收录，4 个不相关或非 skill 过滤；未发现对已装 skill 的更好替代品；anthropics/skills 复查无会话记忆类新 skill，无需新装。
- 2026-11-05：会话存档访问第 3 次被权限拒绝，沿用 2026-11-02 调用统计（grill-me 7、novel-atlas 3、xhs-story 1、promo-atlas 1、humanizer-zh 0、longform 0）。无删除项：humanizer-zh/longform 受用户级 MEMORY.md 保护，其余均在近期有调用；topic 页未发现对 humanizer-zh 的更好替代品（blader/humanizer 为英文上游，已作参考同步）。self-improving-agent 上游复查无更新，anthropics/skills 无会话记忆类新 skill。
- 2026-11-04：会话存档访问再次被权限拒绝，沿用 2026-11-02 调用统计（grill-me 7、novel-atlas 3、xhs-story 1、promo-atlas 1、humanizer-zh 0、longform 0）。无删除项：humanizer-zh/longform 受用户级 MEMORY.md 保护，其余均在近期有调用。self-improving-agent 上游复查无更新。
