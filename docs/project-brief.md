# Project Brief

## 目标

创建一个 GitHub-ready 项目 `learn-xx-prompt`，面向 AI 产品经理讲解如何学习 SOTA agent prompt。

## 用户要求映射

| 用户要求 | 当前实现 |
| --- | --- |
| 起一个 GitHub 项目 | 已创建 `outputs/learn-xx-prompt/` 项目目录，包含 README、LICENSE、CONTRIBUTING、GitHub PR 模板，并已初始化本地 git 仓库与初始提交 |
| 汉化以上提示词 | 已在 `docs/translations/` 提供 7 个 Phistory 样本的中文意译和 PM 导读 |
| 渐进式阅读材料 | 已在 `docs/reading/` 提供 6 篇渐进阅读材料 |
| SVG 等可视化工具 | 已在 `assets/visuals/` 提供 3 个纯 SVG 可视化 |
| 对比各家提示词 | 已提供结构分类、对比雷达、模块覆盖矩阵、中文案例导读和评估 rubric |
| 尽量使用 subagent | 已由 subagent 分别完成资料抽取、阅读材料、SVG 可视化 |

## 当前选择

当前采用“中文意译 + 结构化导读”而不是逐字全文翻译。原因：

- 原始 prompt 很长，机械翻译不利于 PM 学习。
- 大量内容是工具 schema，更适合归纳为产品设计模式。
- 原文以 Phistory 链接为准，项目保留来源索引。

## 发布前待确认

如果要发布到 GitHub 远端，还需要人工确认：

- GitHub owner 或 organization
- 仓库可见性：public / private
- 是否启用 GitHub Pages
- 是否需要把项目名从 `learn-xx-prompt` 改成更明确的 `learn-agent-prompt`
