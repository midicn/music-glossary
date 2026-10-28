---
id: latency-compensation
site: gloss
cat: G7
title: 延迟补偿
title_en: Latency Compensation
summary: 让不同处理链的延迟对齐，避免声部错位
summary_en: Aligning the delays of different chains so parts stay together
level: brief
tags: [制作, 工作流, 延迟]
tags_en: [production, workflow, latency]
alias: [延迟补偿, latency compensation, 延迟校准, 自动延迟补偿]
order: 1987
links:
  - "[[glossary:latency]]"
  - "[[glossary:buffer-size]]"
  - "[[glossary:patchbay]]"
sources:
  - 延迟补偿在 DAW 中的机制，参通行录音教材；本文为原创表述
updated: 2026-10-28
---

::: zh
**延迟补偿（latency compensation）** 是让**不同处理链的延迟对齐**：插件、外部硬件、总线处理都会引入不同的延迟，补偿机制把它们的播放时间对齐，避免声部错位。

它和**缓冲大小**不同：缓冲影响**输入输出延迟**，补偿处理的是**各条链之间的相对延迟**。**常见误解是「延迟只影响演奏手感」**——录音回放时，未补偿的延迟会让叠录的声部**错开**；**补偿是叠录与混音对齐的基础。**

深入阅读 → [[glossary:latency]]
:::

::: en
**Latency compensation** aligns the **delays of different processing chains**: plugins, external hardware and bus processing each add different delays, and the system shifts playback so the parts stay together.

It differs from **buffer size**: the buffer affects **input/output latency**, while compensation handles **relative delay between chains**. **The usual mistake is to think latency only affects playing feel** — on playback, uncompensated delay makes overdubbed parts **drift**; **compensation is the basis of alignment in overdubbing and mixing.**

Read deeper → [[glossary:latency|latency]]
:::
