# Love Wheel（恋爱话题＆活动转盘）题库 v0

风格：俏皮轻松，但能聊到关键价值观。

- `question_bank_v0.json`：题库（10 主题 × 8 题 = 80 题）

## 字段说明
- `id`：题目唯一编号
- `topic`：主题
- `text`：题干
- `options`：选项（2-5 个）
- `followUps`：追问（引导把抽象聊具体）
- `flags`：标签（redflag/boundary/money/family/conflict/values/lifestyle 等）

## 用法建议（产品交互）
- 转盘抽题 → 双方盲选 → 再显示对方答案 → 进入追问页
- `flags` 为 redflag 的题：显示“认真聊聊”提示，不做价值评判
