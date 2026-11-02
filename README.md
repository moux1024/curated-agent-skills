# Curated Agent Skills（与本地会话内容相关）

整理自 https://github.com/topics/agent-skills（2026-11-02），筛选标准：与本地工作流相关——中文长文写作、小红书/推广内容、可视化图解、跨会话改进。

## 写作与去模板化

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [blader/humanizer](https://github.com/blader/humanizer) | 63k | 2026-10-28 | 去除 AI 生成痕迹的写作 skill。本地已有其中文定制版 `humanizer-zh`，仅作上游参考 |

## 营销与内容增长

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 57.7k | 2026-10-31 | CRO、文案、SEO、增长工程，与小红书推广工作流相关 |

## 设计与反 AI slop

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 107k | 2026-10-31 | 给编码 agent 设计品味：艺术方向、参考图、浏览器检查 |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 98.3k | 2026-10-31 | 设计词汇表，polish/critique/audit，拦截 AI slop |

## 可视化与图解

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | 92.2k | 2026-10-31 | 把想法/计划/代码库变成交互式图表，对 novel-atlas 类图解任务有参考价值 |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 63.5k | 2026-10-27 | 编辑级图表设计，45 种图型，自包含 HTML+SVG |

## 跨会话自我改进

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [pskoett/self-improving-agent](https://github.com/pskoett/self-improving-agent) | 786 | 2026-10-31 | 跨会话沉淀 learnings/errors/corrections，持续优化历史会话效果。**已安装到本地** |

## 综合索引

| 仓库 | Stars | 更新 | 说明 |
|------|-------|------|------|
| [anthropics/skills](https://github.com/anthropics/skills) | 186k | 2026-10-28 | Anthropic 官方 Agent Skills 仓库 |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | 78.5k | 2026-09-18 | Claude Skills 精选列表 |

---
*由 WorkBuddy 自动化整理生成，数据截取自 2026-11-02 的 GitHub 话题页。*

## 已基于本清单反向优化自建 skill（2026-11-02）

| 自建 skill | 参照来源 | 改动 |
|------------|---------|------|
| humanizer-zh v2.1.0 | blader/humanizer v3.1.0 | 同步两条总规则、结构/词表严重度分级、幸存模式复查步（1/2/6/8/19）、词表衰减说明；description 加触发推力 |
| longform v0.1.1 | anthropics/skills 官方规范 | 修复死指针（xhs-replica）、专家包引用加降级说明、description 触发推力 |
| xhs-story v1.1.1 | marketingskills/copywriting | Step 5 注入三问门（画面化/可证伪/竞品换位）、punch 配给、[NEED] 缺料标记 |
| promo-atlas v1.0.2 | marketingskills/copywriting | copy-voice.md 新增换位测试与 punch 配额，接入交付前六问 |
| novel-atlas v0.5.0 | — | 审计通过：渐进披露、copy 复查、references 均达标，无需改动 |
