# Market Research Landing Lab

## 🚀 快速开始

**如果你刚从这个模板派生出一个新项目,第一步只需一句话:**

> 打开 Claude Code,输入 **"开始这个项目"**

Claude 会自动进入访谈流,依次收集:

1. 执行人核心技能
2. 当前渠道现状
3. 长期护城河方向
4. 启动约束(时间 / 资金 / 月收入目标)

访谈结束后,答案会直接写入 `docs/00-research-question.md` 的"执行人前提确认"章节,并给你看 diff 再决定是否提交。

> 其他等效触发词:"启动项目" / "初始化这个项目" / "start this project"
>
> 如果 Claude 没自动识别,直接说"用 start-project skill 启动"即可。

---

## 仓库定位

这是一个用于"市场调研和落地方案探讨"的**决策仓库**,不是产品代码仓库。

本仓库的目标是帮助后续的 Claude Code、Codex、ChatGPT 围绕同一套文档结构推进:

1. 市场调研
2. 竞品分析
3. 短期现金流项目筛选
4. 长期护城河项目设计
5. MVP 冻结与执行切换

## 不是用来做什么

- 不写前端代码
- 不写后端代码
- 不写 App 代码
- 不写数据库代码
- 不自动开始调研
- 不在没有证据的情况下产出市场结论

## 核心记录规则

所有调研与决策文档都必须尽量使用三段式:

### 证据

- 来源是什么
- 看到的原始信息是什么
- 缺了什么信息

### 推断

- 基于现有证据可以做出什么有限判断
- 推断的置信度如何
- 哪些地方仍然需要验证

### 决策

- 当前是否继续
- 当前是否淘汰
- 下一步要补哪类证据

## 毕业条件

当以下问题都有可执行答案时,停止调研并进入项目执行:

1. 第一版做什么
2. 第一版不做什么
3. 7 天 Demo 范围
4. 30 天 MVP 范围
5. 第一个收费点
6. 短期项目如何反哺长期护城河

## 完整工作流

1. 首次初始化:用上面的"快速开始"填 [docs/00-research-question.md](docs/00-research-question.md)
2. 补充 `research/` 下的原始材料和卡片(用 [docs/templates/evidence-card.md](docs/templates/evidence-card.md) 落盘)
3. 更新 `docs/01-09` 中的结构化判断
4. 把阶段性结论沉淀到 `decisions/` ADR

## 目录说明

- `ai/`:多 Agent 协作的任务、状态、结果、交接模板
- `docs/`:结构化研究与决策文档(`00-09` 为固定管线)
- `docs/templates/`:跨文档引用的公共模板(资产复用矩阵、证据卡格式)
- `research/`:原始材料和证据卡片
  - `raw/` 原始资料,`source-cards/` 事实卡,`competitor-cards/` 竞品卡,`user-cards/` 用户卡
- `decisions/`:关键决策 ADR
- `prompts/`:不同 Agent 的提示词
- `skills/`:项目内可复用的工作流契约
- `.claude/skills/`:Claude Code 自动触发的 skill(如 `start-project`)
