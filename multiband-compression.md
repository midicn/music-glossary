---
id: multiband-compression
site: gloss
cat: G7
title: 多段压缩
title_en: Multiband Compression
summary: 分频段独立压缩，只控制需要控制的频段
summary_en: Compressing separate frequency bands independently so only problem ranges are controlled
level: brief
tags: [制作, 压缩, 频率]
tags_en: [production, compression, frequency]
alias: [多段压缩, multiband compression, 多频段压缩, 分频压缩]
links:
  - "[[glossary:compressor]]"
  - "[[glossary:eq]]"
  - "[[glossary:dynamic-eq]]"
sources:
  - 多段压缩的原理与分频，参 Bob Katz, Mastering Audio 与 Bobby Owsinski, The Mixing Engineer's Handbook
updated: 2026-10-28
---

::: zh
**多段压缩（multiband compression）** 把信号分成几个频段，各自独立压缩后再合起来。这样低频的鼓点不会触发整段音乐一起抽吸，只处理需要控制的那一段。

它常用于混音总线与贝斯：低频压紧，中高频保持开放。分频器本身会带来相位与延迟，段数越多、交叉越复杂，越要检查合起来是否仍然自然。

常见误解是段数越多越精细。多数素材用两到三段就够；分得太细，听感容易松散，也难判断是哪一段在起作用，频段基础见 [[glossary:eq]]。
:::

::: en
**Multiband compression** splits a signal into several frequency ranges, compresses each one independently, then sums them again. A kick in the low end no longer triggers the whole mix to pump; only the range that needs control is compressed.

It is common on the mix bus and on bass: tighten the lows while keeping the mids and highs open. The crossover itself introduces phase shift and delay, so the more bands and crossovers, the more carefully the summed result should be checked.

The usual mistake is to assume more bands mean more precision. Two or three bands cover most material; splitting too finely loosens the sound and makes it hard to tell which band is doing the work.
:::
