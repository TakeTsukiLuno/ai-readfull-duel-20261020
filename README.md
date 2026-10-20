# 双 AI「读全」交叉测试｜2026-10-20

**龙娘（GPT-6） × 大肥鱼（DSH）｜人工中继双向测试**

本仓库为实验对话的独立文字档案。核心证据在 [original/transcript_duel_only.md](original/transcript_duel_only.md)：以 DSH 方 `transcript.md` 为依据，**仅删除全部 `### 你的插话` 及其从属内容（包括模板栏）**，保留双方对话、测试题面、答卷、判分和终局总结。删除记录见 [original/REDACTION_LOG.md](original/REDACTION_LOG.md)。

**重要边界：** 这是人工中继整理的档案副本，并非两侧独立抓取、交叉确认的 API 原生日志。文内状态与结算段属于 DSH 方事后记录，不能与即时发言混同。

## 文档
- [original/transcript_duel_only.md](original/transcript_duel_only.md)：R1–R11 清理后的对话与终局记录
- [archive/01_PROTOCOL.md](archive/01_PROTOCOL.md)：协议演进与停手规则
- [archive/02_ROUNDS_AND_SCORES.md](archive/02_ROUNDS_AND_SCORES.md)：五轮裁决与分数
- [archive/03_VERBATIM_EXCERPTS.md](archive/03_VERBATIM_EXCERPTS.md)：关键原文摘录
- [archive/04_PROVENANCE.md](archive/04_PROVENANCE.md)：档案来源与边界
- [archive/questions/](archive/questions/)：五轮原题
- [skills/](skills/)：DSH 编写的人工中继及读全交叉核验 Skill

## 双方确认的成绩

| 轮次 | 出题 | 答题 | 判定 | 得分 / 4 |
|---|---|---|---|---:|
| R3 | DSH | 龙娘 | 通过（偏移留档） | 3.5 |
| R4 | 龙娘 | DSH | 未通过（主体错置） | 3.0 |
| R5 | 龙娘 | DSH | 通过（轻微外延） | 3.5 |
| R8 | DSH | 龙娘 | 通过 | 4.0 |
| R9 | 龙娘 | DSH | 未通过（证据层级上移） | 2.0 |

- 龙娘：平均 **3.75/4 = 93.75/100**
- DSH：平均 **2.8333/4 ≈ 70.83/100**
- 题目数量、难度未校准；此结果不是稳定能力排行榜。
- 校验串均一致，但未形成独立中继复核的证据。

本仓库只保存对线文字；视频 V3、透明角色素材、字幕和 Codex 配音工程另行交接，不将影视化台词当成实验原话。
