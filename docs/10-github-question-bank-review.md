# GitHub 题库检索与授权审查

> 检索与复核日期：2026-07-22。完整机器可读清单见 `question-bank/github-source-catalog.csv`。

## 结论

GitHub 上确实存在多个“系统架构设计师真题库”，但“公开仓库”不等于“题目可自由转载”。本次将候选来源分为三档：

1. **可镜像的原创模拟题**：上游明确声明原创，并用开放许可证授权；
2. **只可链接的真题聚合**：仓库代码可能开源，但真题正文版权没有随代码许可证转移；
3. **不建议使用的资料包**：含教材扫描、OCR、网盘或来源不清的出版物。

最终只镜像 `wujiaming88/awesome-ruankao` 中明确标注为原创的 2026 年 5 月模拟卷 1，并固定到提交 `16093de843f618c7c35af3e83b47644b5fae2c6f`。该套题及解析按 CC BY-SA 4.0 共享；上游的历年真题正文没有复制。

## 有价值但只保留链接的题库

### Zhang-986/ruankao-architect-practice

- 仓库：<https://github.com/Zhang-986/ruankao-architect-practice>
- 在线练习：<https://zhang-986.github.io/ruankao-architect-practice/>
- 仓库自述规模：1,822 道选择题、78 道案例题、60 道论文题，覆盖 2009—2025 年。
- 判断：适合在线刷题和交叉核对，但其 MIT 许可证主要覆盖程序代码；NOTICE 对真题另作版权提示，因此本仓库不复制题目正文。

### YoungHong1992/ruankao-senior-architecture-designer

- 仓库：<https://github.com/YoungHong1992/ruankao-senior-architecture-designer>
- 特点：教程 OCR、历年试题清洗和约 36 套考试资料。
- 判断：仓库自己的 `CONTENT_POLICY.md` 已说明未获得第三方内容授权，MIT 仅覆盖脚本和工作流，因此只保留链接。

### 其他候选

`fukai000/ruankao-architecture` 和 `cycleuser/ruankao-architect-practice` 与 Zhang-986 数据关系紧密，不能当成独立证据源；`xxlllq/system_architect`、`xxlllq/ruankao_exam` 等资料包未见覆盖正文的明确许可证，且可能含教材或出版物，因此不复制。

## 本仓库采取的边界

- 开放许可证必须能明确覆盖“题目和解析正文”，只给软件代码的 MIT 许可证不够。
- 上游说“仅供学习交流”不是开放转载授权。
- 真题原出题方的权利声明优先于聚合仓库的代码许可证。
- 可合法共享的原创模拟题必须保留作者、原始链接、固定版本、许可证和修改说明。
- 来源不清的真题仅用来统计主题，不逐字入库；练习内容采用重新设计的题干、场景和数据。

## 如何继续扩充

后续发现新仓库时，先在 CSV 中补齐 `license_or_notice`、`reuse_decision` 和 `pinned_revision`。只有 `reuse_decision` 通过，才把正文放入 `question-bank/open-source/`；否则只加链接。若用户本人拥有正版资料或权利方书面授权，可另建私有目录，但不要把受限文件推入公开仓库。
