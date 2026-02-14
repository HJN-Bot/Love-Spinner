# Love-Spinner（恋爱话题转盘）

目标：把尴尬的深聊变成轻量游戏：**盲选作答 → 聊一聊 → 协商一个“我们答案”**。

## 在线体验（GitHub Pages）
- 打开：`https://hjn-bot.github.io/Love-Spinner/`

> 如页面 404，说明 Pages 还没开启；稍等我开通后再刷新。

## 仓库内容
- `question_bank_v0.json`：题库（当前版本 88 题）
- `INTERACTION_SPEC.md`：交互规格（双人作答 + 协商答案）
- `docs/index.html`：可直接部署的静态网页（支持导出结果）

## 页面功能
- 选主题 / 全主题混抽
- 双人盲选（男生/我、女生/TA）
- 协商答案（我们）
- 记录每题备注（localStorage）
- 导出结果：JSON / Markdown

## 字段说明（题库）
- `id`：题目唯一编号
- `topic`：主题
- `text`：题干
- `options`：选项（2-5 个）
- `followUps`：追问（引导把抽象聊具体）
- `flags`：标签（redflag/boundary/money/family/conflict/values/lifestyle 等）

## 本地开发
直接打开 `docs/index.html` 即可（纯静态，无构建）。
