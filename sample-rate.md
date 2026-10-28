---
id: sample-rate
site: gloss
cat: G7
title: 采样率
title_en: Sample Rate
summary: 每秒采样的次数，决定可记录的最高频率
summary_en: Samples captured per second; the ceiling on the frequencies a system can represent
level: brief
tags: [音频, 采样, 制作]
tags_en: [audio, sampling, production]
alias: [采样频率, 取样率, sample rate, sampling rate, 44.1kHz, 48kHz]
order: 152
links:
  - "[[glossary:bit-depth]]"
  - "[[glossary:daw]]"
  - "[[concept:pitch]]"
sources:
  - 采样率、奈奎斯特频率与常用工程采样率，参 The New Grove Dictionary of Music and Musicians, "Sound recording" 与 Modern Recording Techniques（Huber & Runstein）；本文为原创表述
updated: 2026-10-28
---

::: zh
**采样率**是每秒对声音信号采样的次数，单位是赫兹。44.1 kHz 每秒取 44,100 个点，48 kHz 取 48,000 个点；点越密，能记录的高频越高，文件也越大。

奈奎斯特定理指出，要记录频率 f，采样率必须高于 2f。44.1 kHz 的理论上限是 22.05 kHz，覆盖人耳 20 kHz 的听觉范围；48 kHz 留出更多余量，成为视频与广播的常用值。96 kHz 以上的收益主要在录音与处理阶段，而不在回放。

常见误解：采样率越高，回放一定越好听。超过听觉上限的频率听不见；高采样率的价值更多在于减少转换与非线性处理的混叠，并给后期留出余量。

相关 → [[glossary:bit-depth]]
:::

::: en
**Sample rate** is the number of times per second an audio signal is sampled, measured in hertz. At 44.1 kHz the system takes 44,100 points each second; at 48 kHz it takes 48,000. Denser points allow higher frequencies to be captured, and make larger files.

The Nyquist theorem states that capturing a frequency f requires a sample rate above 2f. At 44.1 kHz the theoretical ceiling is 22.05 kHz, which covers the 20 kHz limit of human hearing. 48 kHz leaves more margin and is common in video and broadcast. Rates above 96 kHz help mainly in recording and processing, not in playback.

The usual mistake is to assume a higher rate always sounds better on playback. Frequencies above the hearing limit are inaudible; the value of high rates lies more in reducing aliasing in conversion and non-linear processing, and in leaving headroom for later work.

Related → [[glossary:bit-depth]]
:::
