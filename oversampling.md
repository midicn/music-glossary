---
id: oversampling
site: gloss
cat: G7
title: 过采样
title_en: Oversampling
summary: 处理时临时提高采样率，减少混叠失真
summary_en: Processing at a higher rate to reduce aliasing
level: brief
tags: [制作, 音频, 处理]
tags_en: [production, audio, processing]
alias: [过采样, oversampling, 超采样, 升采样处理]
order: 1982
links:
  - "[[glossary:sample-rate]]"
  - "[[glossary:limiter]]"
  - "[[glossary:bit-depth]]"
sources:
  - 过采样在非线性处理中的作用，参通行录音教材
updated: 2026-10-28
---

::: zh
**过采样（oversampling）** 是处理时**临时提高采样率**，处理完再降回原采样率。它主要用在失真、饱和、限制等**非线性处理**里，减少高频折叠回可听频段的**混叠失真**。

它和高采样率录音不同：oversampling 是处理内部的临时升频，不改变工程采样率。常见误解是「过采样会让声音更好」——它的目标是减少处理产生的伪影；在干净的处理里，听感差别可能很小。

深入阅读 → [[glossary:sample-rate]]
:::

::: en
**Oversampling** **temporarily raises the sample rate** for processing, then converts back. It is mainly used in **non-linear processing** such as distortion, saturation and limiting, to reduce **aliasing** folding back into the audible band.

It differs from recording at a high sample rate: oversampling is a temporary internal upsample, not a change to the project rate. The usual mistake is to expect it to "improve" the sound — its goal is fewer processing artifacts; in clean processing the audible difference can be small.

Read deeper → [[glossary:sample-rate|sample rate]]
:::
