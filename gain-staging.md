---
id: gain-staging
site: gloss
cat: G7
title: 增益结构
title_en: Gain Staging
summary: 在信号链每一级设定合适电平，既不削波也不埋进噪声
summary_en: Setting the right level at every stage so nothing clips and nothing sinks into noise
level: brief
tags: [制作, 电平, 信号链]
tags_en: [production, level, signal chain]
alias: [增益结构, gain staging, 增益级联, 电平结构]
order: 532
links:
  - "[[glossary:headroom]]"
  - "[[glossary:clipping]]"
  - "[[glossary:eq]]"
sources:
  - 增益结构与标称电平，参 Huber & Runstein, Modern Recording Techniques 与 Bob Katz, Mastering Audio 的通行论述
updated: 2026-10-28
---

::: zh
**增益结构（gain staging）** 指在信号链的每一级——话筒放大、插件、总线、输出——把电平设在该级的合适区间：足够高以远离噪声底，又留出余量不撞削波。模拟设备有标称电平，许多数字插件也按某个电平设计。

通常让每级接近单位增益，只在需要时提升或衰减；用表头看峰值与平均电平，而非只凭听感。多级累积容易越推越响，最后在总线上削波。**通行说法**是 0 VU 约对应 -18 dBFS，留 18 dB 余量，但设备与素材并不统一。

常见误解是把它当成把所有东西推到最大。24 位录音录得保守不会损失有效分辨率；每级都顶满，只会把失真留到最后。

相关 → [[glossary:headroom]]
:::

::: en
**Gain staging** means setting the level at every stage — preamp, plug-ins, buses, output — into that stage's sweet spot: high enough to clear the noise floor, low enough to leave headroom before clipping.

Aim for roughly unity gain at each stage, boosting or cutting only where needed, and read peaks and average level on meters rather than by feel. Cumulative gain makes a chain louder until the bus clips. The rule of thumb maps 0 VU to about -18 dBFS, leaving 18 dB of headroom, though gear and material vary.

The usual mistake is to treat gain staging as "turn everything up". At 24-bit, recording conservatively costs no useful resolution; making every stage peak only saves distortion for the end.

Related → [[glossary:headroom]]
:::
