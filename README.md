# 系统架构设计师备考资料库（2026·广东）

面向 2026 年广东考区“系统架构设计师”高级资格考试的原创备考资料库。当前主目标是 **2026 年下半年考试**，资料以官方通知为准，配合知识地图、复习计划、案例分析方法和论文训练模板使用。

> 更新基准日：2026-07-22。考试政策可能调整，临考前务必再次核对广东人事考试网、中国计算机技术职业资格网和本人准考证。

## 2026 年下半年关键时间

| 事项 | 广东考区时间（北京时间） |
| --- | --- |
| 报名信息填报 | 2026-08-17 09:00 ～ 2026-08-25 17:00 |
| 网上缴费 | 2026-08-17 09:00 ～ 2026-08-26 17:00 |
| 准考证打印 | 2026-10-20 09:00 ～ 2026-10-23 17:00 |
| 考试日期范围 | 2026-10-24 ～ 2026-10-27 |

系统架构设计师在 2026 年上下半年均开考。下半年个人的具体考试日期、时间、地点和批次 **以准考证为准**。

## 考试结构

系统架构设计师属于高级资格，设置三个科目：

1. 信息系统综合知识：选择题；
2. 系统架构设计案例分析：问答题；
3. 系统架构设计论文：论文题。

现行高级资格机考采用“综合知识 + 案例分析”连考，两个科目总作答时长 240 分钟；论文科目 120 分钟。各科目必须在同一次考试中全部达到当次合格标准，才可取得资格证书。广东官方文件说明合格标准原则上为各科满分的 60%，如遇政策调整则以最新通告为准。

## 如何使用本仓库

1. 先读 [2026 广东报考与考试信息](docs/00-2026-guangdong-exam.md)，设置报名、缴费和准考证提醒。
2. 按 [官方大纲与教材索引](docs/01-official-resources.md) 准备正版大纲、教程和官方试题解析。
3. 用 [知识地图](docs/02-knowledge-map.md) 做一次自评，标记薄弱域。
4. 从当前日期开始执行 [13 周备考计划](docs/03-study-plan.md)。
5. 分别训练 [案例分析](docs/04-case-analysis.md) 与 [论文](docs/05-essay-guide.md)，不要等综合知识学完才开始。
6. 冲刺阶段使用 [速查表](docs/06-architecture-quick-reference.md) 和 [考前清单](docs/07-exam-day-checklist.md)。
7. 在 [进度表](tracker/progress.csv) 中记录每周完成度、正确率和论文产出。
8. 用 [2023—2026 真题主题与变化分析](docs/08-past-paper-trend-analysis.md) 调整复习权重；需要追溯证据时查看 [真题数据源使用指南](docs/09-past-paper-source-guide.md) 和 `data/` 下的 CSV。

## 仓库结构

```text
.
├── README.md
├── data/
│   ├── past-paper-source-catalog.csv
│   └── past-paper-topic-index.csv
├── docs/
│   ├── 00-2026-guangdong-exam.md
│   ├── 01-official-resources.md
│   ├── 02-knowledge-map.md
│   ├── 03-study-plan.md
│   ├── 04-case-analysis.md
│   ├── 05-essay-guide.md
│   ├── 06-architecture-quick-reference.md
│   ├── 07-exam-day-checklist.md
│   ├── 08-past-paper-trend-analysis.md
│   ├── 09-past-paper-source-guide.md
│   └── references.md
├── templates/
│   ├── case-answer-sheet.md
│   └── essay-outline.md
└── tracker/
    └── progress.csv
```

## 资料原则

- **官方优先**：考试日期、批次、科目和合格标准以官方通知为准。
- **理解优先**：架构题重在“场景—质量属性—决策—权衡—验证”，不以背术语代替分析。
- **真题闭环**：完整旧题优先使用正版官方解析书；近年回忆题只入库来源、主题、可信度和错因，不转载受版权保护的整套试题。
- **项目真实**：论文素材来自自己真实参与或可如实说明的项目，避免万能模板和虚构数据。

## 官方入口

- [中国计算机技术职业资格网](https://www.ruankao.org.cn/)
- [广东人事考试网：2026 年报考须知](https://rsks.gd.gov.cn/zwgk/gzdt/content/post_4871651.html)
- [系统架构设计师考试说明](https://www.ruankao.org.cn/article/content/ksjs/03_03.html)
- [官方考试用书页面](https://www.ruankao.org.cn/book/main.html)

## 版权说明

本仓库只保存原创整理、公开政策链接、书目信息和个人学习模板，不收录盗版教材、未经授权的扫描件或整套试题。引用外部资料时请遵守原网站和出版物的版权声明。
