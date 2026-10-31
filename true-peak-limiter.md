---
id: true-peak-limiter
site: gloss
cat: G7
title: 真峰值限制器
title_en: True-Peak Limiter
summary: 连采样点之间的峰值也一起限制，防止转换后削波
summary_en: Limiting inter-sample peaks too, so conversion does not clip
level: brief
tags: [制作, 母带, 峰值]
tags_en: [production, mastering, peak]
alias: [真峰值限制器, true-peak limiter, 真峰限制, 采样间峰值]
order: 1986
links:
  - "[[glossary:limiter]]"
  - "[[glossary:loudness-normalization]]"
  - "[[glossary:sample-rate]]"
sources:
  - 真峰值（inter-sample peak）与限制，参通行母带教材；本文为原创表述
updated: 2026-10-28
---

::: zh
**真峰值限制器（true-peak limiter）** 不只限制采样点的峰值，还限制**采样点之间**可能出现的更高峰值（inter-sample peak）。它避免音频在转成模拟或编码后发生削波。

它和普通**限制器**不同：普通限制器看的是采样值，真峰值限制器看的是**重建后的波形**。常见误解是「采样值不超 0 dBFS 就不会削波」——采样点之间仍可能超出；真峰值限制是上传播放前的最后一道保险。

深入阅读 → [[glossary:limiter]]
:::

::: en
**A true-peak limiter** limits not only the sample values but the **higher peaks that can occur between samples** (inter-sample peaks). It prevents clipping after conversion to analog or a lossy codec.

It differs from a normal **limiter**: a normal limiter watches sample values, a true-peak limiter watches **the reconstructed waveform**. The usual mistake is to think "samples below 0 dBFS means no clipping" — peaks can still exceed between samples; true-peak limiting is the last insurance before delivery.

Read deeper → [[glossary:limiter|limiter]]
:::
