# coding-eval

BAI AI Lab 代码能力阶梯评测的结果网站：https://bai-ai-lab.github.io/coding-eval/

- 题目：五档 112 题。L1–L4 为 USACO 2024–25、2025–26 赛季的铜、银、金、铂金组与 EGOI 2026，L5 为 FrontierCS 算法赛道的 30 道开放式难题；每题有英文原题面（USACO 官网页面、EGOI 2026 官方 PDF、FrontierCS 的 statement.txt）和原题链接。
- 原理：阶梯基准、判题与计分、运行效率与复杂度、静态代码质量、统计方法、调用设置、提示词、被测模型、归因规则、智能体评测，以及参考文献。
- 结果：Kimi K3.1 Pro（high 与 max）、DeepSeek Flash V4.1-1017、MiniMax M3.1 Flash 的各档正确率与 95% 区间、两两比较、思考强度、新旧题对照、运行效率与复杂度、失败类型、代码质量、用量与费用、厂商声称对照，以及全部答案代码。
- 自定义评测：在服务器上用 codingBench 的 `cb ladder` 评测自己的模型的命令与参数手册。
- 报告：`report-2026-11-03.pdf`。数据：`data/ladder.json`。
- 上一版评测（LiveCodeBench 最新 35 题，2026-10-23）保留在 `archive/2026-10-23/`。
- 题面版权归 USACO、EGOI 与 FrontierCS，本站转载官方英文原文并附原题链接；测试数据不公开。数学公式用自带的 KaTeX 0.16.11（MIT）渲染。

本仓库内容由 codingBench 的 `reports/2026-11-03_ladder_technical_report/site.py` 生成，不要手改；修改生成器后重新生成并推送。
