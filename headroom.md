---
id: headroom
site: gloss
cat: G7
title: 余量
title_en: Headroom
summary: 当前电平与削波上限之间的安全空间，给峰值留余地
summary_en: The safety margin between your working level and the clipping ceiling
level: brief
tags: [制作, 电平, 动态]
tags_en: [production, level, dynamics]
alias: [余量, headroom, 动态余量, 峰值余量]
order: 533
links:
  - "[[glossary:gain-staging]]"
  - "[[glossary:clipping]]"
  - "[[glossary:bit-depth]]"
sources:
  - 数字余量与峰值表，参 Bob Katz, Mastering Audio 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-10-28
---

::: zh
**余量（headroom）** 是当前电平与削波上限之间的空间。数字领域 0 dBFS 是硬上限，超过就削波，因此录音、混音与母带都要在峰值之上留安全带。24 位录音动态范围很宽，平均电平录到 -18 dBFS 左右并不浪费分辨率。

混音总线通常留 3–6 dB 峰值余量，母带再决定最终响度；若总线已贴着 0 dBFS，均衡或压缩的增益变化就可能立刻削波。**通行说法**是先留余量再谈响度：响度在母带阶段解决，不在每一轨上预支。

常见误解是录得越热越好。那是磁带时代的经验；数字录音没有底噪随电平升高的同等收益，反而更容易在采样间峰值上出问题。

相关 → [[glossary:clipping]]
:::

::: en
**Headroom** is the space between the working level and the clipping ceiling. In digital audio 0 dBFS is a hard limit, so recording, mixing and mastering all need a safety margin above the peaks. A 24-bit recording has so much range that averaging around -18 dBFS costs no useful resolution.

A mix bus usually keeps 3–6 dB of peak headroom, and mastering decides final loudness. If the bus already sits at 0 dBFS, any gain change from EQ or compression can clip at once. Leave headroom first and talk about loudness later: loudness belongs to mastering, not to every track.

The usual mistake is to record as hot as possible. That habit comes from tape; digital recording gains no equivalent noise benefit, and is more likely to trip on inter-sample peaks.

Related → [[glossary:clipping]]
:::
