# 横向对比入口

这个目录用于把 7 个 Phistory prompt 样本放到同一张产品地图上看。

## 推荐读法

1. 先看 [模块覆盖矩阵](module-coverage-matrix.md)，确定各家 prompt 的重点模块。
2. 再看 [提示词分层模型](../../assets/visuals/prompt-layer-model.svg)，理解模块之间的上下游关系。
3. 然后看 [对比雷达](../../assets/visuals/agent-comparison-radar.svg)，用它做团队讨论。
4. 最后回到 [中文意译](../translations/README.md)，读具体案例。

## 最适合的对比组合

| 对比组合 | 适合看什么 |
| --- | --- |
| Codex CLI vs opencode | 工程协作 vs 高自主推进 |
| Claude Code vs OpenClaw | 平台 harness、记忆和长期任务 |
| Hermes Agent vs Kimi CLI | 工具目录、计划模式、委派机制 |
| Pi vs 其他 6 家 | 最小 prompt 如何演进成平台级 prompt |
| Codex CLI vs Claude Code | 输出规范、权限边界和多代理能力 |

## 讨论问题

- 哪一家最像你的产品目标？
- 哪一家最不适合照抄？为什么？
- 你的 agent 需要强自主，还是强确认？
- 哪些规则应该写进 prompt，哪些应该变成产品权限机制？
- 如果只做 3 条评估用例，最应该覆盖哪 3 个风险？

## 数据说明

对比雷达的可审计数据见 [data/agent-comparison-radar.json](../../data/agent-comparison-radar.json)。分值是教学用相对侧重，不代表真实能力排行。
