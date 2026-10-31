---
id: sampler
site: gloss
cat: G7
title: 采样器
title_en: Sampler
summary: 把录音采样映射到键盘演奏的乐器
summary_en: An instrument that maps recorded samples across the keyboard
level: brief
tags: [制作, 乐器, 采样]
tags_en: [production, instrument, sampling]
alias: [采样器, sampler, 采样播放器]
order: 539
links:
  - "[[glossary:plugin]]"
  - "[[glossary:midi-protocol]]"
  - "[[glossary:sample-rate]]"
sources:
  - 采样器架构与映射，参 Huber & Runstein, Modern Recording Techniques 与通行采样器手册
updated: 2026-10-28
---

::: zh
**采样器（sampler）** 是把录音样本映射到键盘的乐器：每个键触发一个样本，按力度分层、按音域分区，再用循环、包络、滤波器与调制把它变成可演奏的音色。鼓组常用 one-shot，钢琴与弦乐则靠多层多采样还原动态。

它和合成器的区别在声源：采样器播放录好的声音，合成器用振荡器生成波形。采样器也不是采样库本身——库是素材，采样器是播放与塑形它的引擎。

常见误解是采样器只是播放 loop。它可以重排、变调、切碎与重新包络；真正限制它的是样本质量与映射功夫。

相关 → [[glossary:midi-protocol]]
:::

::: en
A **sampler** is a software or hardware instrument that maps recorded samples across a keyboard: each key triggers a sample, with velocity layers, key zones, loops, envelopes, filters and modulation making it playable. Drum kits often use one-shots, while pianos and strings use multiple layers and samples to preserve dynamics.

It differs from a synthesizer in its source: a sampler plays recorded sound, a synthesizer generates waveforms, though many products do both. A sampler is also not the sample library itself — the library is material, the sampler is the engine that plays and shapes it.

The usual mistake is to think a sampler only plays loops. It can rearrange, transpose, chop and re-envelope; what limits it is sample quality and mapping care.

Related → [[glossary:midi-protocol]]
:::
