---
id: clipping
site: gloss
cat: G7
title: 削波
title_en: Clipping
summary: 信号超过可表示上限时波形被削平，产生失真
summary_en: When a signal exceeds the maximum level, its waveform is flattened into distortion
level: brief
tags: [制作, 失真, 电平]
tags_en: [production, distortion, level]
alias: [削波, clipping, 削顶, 过载削波]
order: 534
links:
  - "[[glossary:headroom]]"
  - "[[glossary:gain-staging]]"
  - "[[glossary:compressor]]"
sources:
  - 削波与真峰值，参 Bob Katz, Mastering Audio 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-10-28
---

::: zh
**削波（clipping）** 发生在信号超过系统能表示的最大电平时：波形顶部与底部被切平，接近方波，产生大量谐波失真。数字削波通常刺耳、带颗粒感；模拟电路削波较软，常被当作音色使用。

削波不只发生在 0 dBFS：采样之间的真实峰值可能高于样本峰值，在数模转换后照样过载。所以母带要看 dBTP，而不只是采样峰值。限制器把峰值压在阈值之下，但压得太狠会让声音发扁、失去瞬态。

常见误解是表没红就没有削波。单样本表可能漏掉采样间峰值；削波一旦发生，后续再降电平也补不回被切掉的波形。

相关 → [[glossary:headroom]]
:::

::: en
**Clipping** happens when a signal exceeds the maximum level a system can represent: the tops and bottoms of the waveform are sliced flat, turning a curve into something close to a square wave and adding heavy harmonic distortion. Digital clipping usually sounds harsh; analog clipping is softer and often used as tone.

Clipping does not only occur at 0 dBFS. True peaks between samples can sit above the sample peaks and overload the converter anyway, so mastering watches dBTP, not just sample peak. A limiter holds peaks under a threshold, but pushing it too hard flattens the sound and kills transients.

The usual mistake is to assume no red meter means no clipping. A sample-peak meter can miss inter-sample peaks, and once a waveform is clipped, lowering the level later cannot restore what was cut off.

Related → [[glossary:headroom]]
:::
