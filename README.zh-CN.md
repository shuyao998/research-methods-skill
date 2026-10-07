# research-methods-skill

**找不到研究空白？凌晨还在写基金申请书？不确定论文结论有没有证据支撑？**

这是一个 Claude Code skill，把一套实用的科研工作流方法变成按需调用的指导。你在日常科研中提问，Claude 会加载对应方法：有步骤、有判断规则、有检查清单，不是泛泛的建议。

English version: [README.md](README.md)

## 你能得到什么

- **找研究空白，并先验证它是真的。** 建文献库、做关键词分组取交集、找结论相反的成对论文，并对每个候选空白做四问检验。
- **写每句都有证据的基金申请书。** 立项依据的七段骨架（意义、瓶颈、既有方法、局限、空白、你的方法与预实验、关键科学问题），逻辑链清晰、可逐段检查。
- **像调试代码一样排查实验。** 隔离变量、替换部件、排除原因、拆分问题，而不是一次改很多地方。
- **逐句写论文。** 每个论断都要有可见的"事实 → 逻辑 → 结论"桥梁；引言的句子素材库方法；查重的硬阈值。
- **投稿前自查。** 每轮只查一类缺陷：格式、引用、交叉引用、内部矛盾、证据。
- **用数据选导师。** 用发文率和延毕率比较候选 PI，排序依据是你毕业后的目标。
- **研究受挫时的工具。** 处理拖延、注意力分散、被打击、选择困难等问题的具体行动方法。

## 核心原则

- 每个论断都需要证据和逻辑桥梁，没有的话不要写。
- 建一个持续更新的知识库，而不是每次从零开始。
- 测试优于推理：检索、分组、实验、写作都靠结果反馈迭代。
- 模糊的正确远好过精确的错误。估计可以粗，方向不能错。

## 试一试

问 Claude 类似这样的问题：

> 我想在增材制造合金的腐蚀方向找研究空白，然后写基金的立项依据，应该从哪里开始？

或者：

> 我的实验无法复现，给我一个一次只改一个变量的排查顺序。

Claude 会加载对应的参考文件并按步骤执行。

## 安装

把 skill 文件夹复制到 Claude Code 的 skills 目录：

```bash
cp -r research-and-paper-writing-method ~/.claude/skills/
```

## 仓库结构

```
research-and-paper-writing-method/
├── SKILL.md                              入口：触发条件、参考索引、核心原则
└── references/
    ├── 01-topic-selection-and-literature.md
    ├── 02-experimental-debugging.md
    ├── 03-paper-writing-method.md
    ├── 04-writing-checklist.md
    ├── 05-keyan-advisor-selection.md
    ├── 06-keyan-sentence-bank-writing.md
    ├── 07-keyan-literature-search-grouping.md
    ├── 08-keyan-topic-selection-and-ideas.md
    ├── 09-keyan-secondary-grouping-verification.md
    ├── 10-keyan-paper-selfcheck-checklist.md
    ├── 11-keyan-mindset-modular-tools.md
    └── 12-keyan-proposal-writing.md
```

## 关于来源

方法内容提炼自公开出版的科研方法论著作与公开的研究方法资料。书中和课程中的具体案例、人名、机构和个案都已删除，保留的示例均标注为假设。本仓库不复制任何原文。

如果你是权利人并认为某些内容侵犯了你的权益，请开 issue，相关内容会被删除。
