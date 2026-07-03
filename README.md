# 🧠 Socratic Lab · 苏格拉底式学习

不给答案，只把你问懂。三个主题从零到深：**狭义相对论 · 期权定价 · 计量经济学**。

**Live:** https://benjaminjason.github.io/socratic-lab/

## 特点
- **AI 苏格拉底导师**：只提问、给渐进提示，绝不直接给答案；答对追问"为什么"防蒙；按表现动态调难度
- **知识图谱**：33 个节点，每个含概念卡、渐进问题、常见误区、依赖关系；力导向图可视化
- **掌握度追踪 + 间隔复习**：AI 评估 0-100 分，随遗忘曲线衰减，首页提示"该复习了"
- **费曼检验**：向 AI 扮演的"聪明高中生"讲清一个主题，AI 天真追问并评分
- **概念卡按需 AI 翻译**、进度导出/重置、深色模式、手机优先、中英切换

## 用法
纯静态单页（Preact + htm，无需构建）。打开后填入 [Anthropic API Key](https://console.anthropic.com)（BYO，仅存本机浏览器）即可启用 AI 导师；概念卡与进度无需 Key 即可浏览。

## 技术
Preact + htm（轻量、无 Babel）· localStorage 持久化 · Anthropic claude-sonnet-4-6（浏览器直连）
