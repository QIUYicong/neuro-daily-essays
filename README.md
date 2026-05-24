# neuro-daily-essays

一个**会自我进化的神经科学 Wiki 知识库**。每天基于官方、可追溯、开放全文的资料创作一篇中文神经科学深度文章，并把其中的知识"固结"进一个不断修订加深的 wiki，长期构建一张"大脑如何从细胞、突触与网络中生长出世界模型"的认知地图。

## 架构：情景—语义双层

借用大脑的记忆原理：每日文章是**情景记忆**（带时间戳、永不改写），wiki 是**语义记忆**（活的、持续修订），每日的固结步骤把前者整合进后者。

```
KNOWLEDGE-BASE-DESIGN.md   # 领域无关的设计方案（可移植到其他知识库）
ROUTINE.md                 # 每日运行指令（操作手册）

neuro-daily/
  articles/   # 情景层：每日文章（append-only）
  notes/      # 情景层：阅读笔记
  sources/    # 情景层：来源元数据
  logs/       # 情景层：运行日志

  wiki/       # 语义层：活的主题页（持续修订）
    index.md          # 全库地图（人读）
    _graph.json       # 知识图谱：节点 + 有类型的边（机读）
    CHANGELOG.md      # 每日 wiki 变更
    _TEMPLATE.md      # 新页模板
    <domain>/<slug>.md

  state/      # 治理层
    topic_ledger.json        # 每日产出台账
    maturity_index.json      # 每页成熟度/置信度
    contested_claims.json    # 矛盾登记册（防腐核心）
    unresolved_questions.md  # 未解问题队列（驱动选题）
    source_registry.json     # 已用来源
    monthly_synthesis.md     # 月度大图景
```

## 核心机制

- **每日固结**：文章触及的每个概念都在 wiki 有家——已有则修订加深，没有则新建。
- **矛盾协议**：新证据与旧主张冲突时不静默覆盖，而是显式登记、降置信度、如实并列。
- **成熟度模型**：`speculative → emerging → mainstream → established`（出现反例则 `contested`），随证据流动。
- **缺口驱动选题**：知识图谱中的悬空引用、待裁决矛盾、高连接低置信节点，告诉系统下一步该学什么。

详见 [`KNOWLEDGE-BASE-DESIGN.md`](KNOWLEDGE-BASE-DESIGN.md)。该设计领域无关，可移植到任何持续学习的知识库。

## 来源原则

只用官方、开放全文来源（PubMed/PMC/Europe PMC、NIH/NINDS/NIMH/BRAIN Initiative/Allen Institute 等）。禁止 Sci-Hub、盗版、绕过 paywall。无开放全文者只用摘要并显式标注。不提供任何医学诊断或治疗建议。
