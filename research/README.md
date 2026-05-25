# Research

原始材料和证据卡片的落盘区。结构化判断放在 `docs/`，最终裁决放在 `decisions/`。本目录保留证据追溯，不承载产品实现规格。

## 子目录

- `raw/` — 原始资料生命周期区；新材料进入 `raw/inbox/`，吸收后移动到 `raw/absorbed/`、`raw/migration/` 或 `raw/deprecated/`
- `source-cards/` — 单条信息的证据卡（一条事实一张卡）
- `competitor-cards/` — 单个竞品的标准化卡（对应 `skills/competitor-card`）
- `user-cards/` — 用户痛点、场景、访谈要点卡

## 规则

- 原始内容不做二次收敛，保留上下文和来源
- `raw/` 根目录不直接放材料文件；避免已处理材料被误判为待处理
- 已吸收材料放 `raw/absorbed/`，后续产品仓库或执行仓库输入放 `raw/migration/`
- 明确不采用但需要留痕的材料放 `raw/deprecated/`
- 每张卡必须有来源链接或可追溯出处，找不到就写"待验证"
- 不把脑补写成事实；信息缺口显式标记
- 结论类内容不放这里，放 `docs/` 或 `decisions/`
