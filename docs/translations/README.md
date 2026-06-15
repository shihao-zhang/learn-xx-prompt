# 中文意译目录

本目录收录 Phistory 中各家 SOTA agent prompt 的中文意译和产品化导读。

## 重要说明

这些文件不是逐字翻译。原因有三点：

1. 原始 prompt 很长，逐字翻译不利于 PM 学习。
2. 多数 prompt 包含大量工具 schema，真正值得学习的是背后的产品设计模式。
3. 原文以 Phistory 快照为准，本项目保留源链接，避免复制整份原文。

因此，每篇会按如下结构写：

- 来源版本
- 一句话定位
- 核心规则意译
- PM 应该学什么
- 可借鉴到自己产品的设计问题

## 当前样本

| 样本 | 最适合对比 | 观察重点 |
| --- | --- | --- |
| [Claude Code: Harness 与记忆](claude-code.zh.md) | OpenClaw、Codex CLI | harness、权限、记忆、多代理 |
| [Codex CLI: 工程协作规约](codex-cli.zh.md) | opencode、Claude Code | 工程判断、交付格式、前端体验 |
| [opencode: 高自主工作流](opencode.zh.md) | Codex CLI、Kimi CLI | 自主性、研究强制、测试闭环 |
| [OpenClaw: 工具生态与长期记忆](openclaw.zh.md) | Claude Code、Hermes | 个人 agent OS、长期记忆、主动性 |
| [Kimi CLI: 工具使用与计划模式](kimi-cli.zh.md) | Hermes、opencode | plan mode、todo、工具边界 |
| [Hermes Agent: 工具目录与委派](hermes-agent.zh.md) | Kimi CLI、OpenClaw | 浏览器工具、委派、记忆卫生 |
| [Pi: 极简 coding agent harness](pi.zh.md) | 所有样本 | 最小 baseline、从简到繁 |
