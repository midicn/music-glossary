---
id: limiter
site: gloss
cat: G7
title: 限制器
title_en: Limiter
summary: 限制峰值的动态处理器；真峰值、采样峰值与输出失真须分别检查
summary_en: A dynamics processor for controlling peaks; check sample peaks, true peaks and distortion separately
level: brief
tags: [制作, 动态, 母带]
tags_en: [production, dynamics, mastering]
alias: [限制器, limiter, 限幅器, 峰值限制]
order: 1983
links:
  - "[[glossary:compressor]]"
  - "[[glossary:true-peak-limiter]]"
  - "[[glossary:lufs]]"
sources:
  - 限制器的参数与母带用法，参通行录音教材
  - https://www.fabfilter.com/help/pro-l/using/truepeaklimiting
  - https://www.fabfilter.com/help/pro-l/using/advancedsettings
updated: 2026-11-03
---

::: zh
**限制器（limiter）**以很高的压缩比控制峰值；部分设计加入前瞻，让处理提前响应将到来的信号。阈值与输出上限（ceiling）的含义依具体产品而定。

**样本峰值限制**与**真峰值限制**不能混用。需要约束dBTP时，选择相应的真峰值模式，导出后重新测量；之后的增益、采样率转换或有损编码仍可能改变峰值。

限制器也会改变声音。过量增益衰减可带来失真、抽吸和瞬态损失；“最大化器”往往也是限制器类产品的名称，并非与限制器严格对立的类别。比较时匹配试听响度，兼顾峰值、动态与听感。

深入阅读 → [[glossary:compressor]] · [[glossary:true-peak]]
:::

::: en
A **limiter** controls peaks with a high compression ratio. Some designs use lookahead to react before a peak arrives. Threshold and output-ceiling controls vary between products.

Sample-peak and true-peak limiting are not interchangeable. When a dBTP limit matters, select a suitable true-peak mode and measure the exported file. Later gain changes, sample-rate conversion or lossy encoding can alter peaks.

Limiting can also cause distortion, pumping and transient loss. A “maximizer” is often a limiter product name, not a strictly separate category. Compare at matched listening loudness rather than treating a ceiling setting as a guarantee of transparency.

Read more → [[glossary:compressor]] · [[glossary:true-peak]]
:::
