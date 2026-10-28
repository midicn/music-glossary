---
id: bit-depth
site: gloss
cat: G7
title: 位深
title_en: Bit Depth
summary: 每个采样用多少位表示，决定理论动态范围
summary_en: How many bits represent each sample, and therefore the theoretical dynamic range
level: brief
tags: [音频, 量化, 制作]
tags_en: [audio, quantization, production]
alias: [位深度, 采样位数, bit depth, bit resolution]
order: 153
links:
  - "[[glossary:sample-rate]]"
  - "[[glossary:daw]]"
sources:
  - 位深、量化噪声与每比特 6 dB 动态范围的通行表述，参 Modern Recording Techniques（Huber & Runstein）与 The New Grove Dictionary of Music and Musicians, "Sound recording"；本文为原创表述
updated: 2026-10-28
---

::: zh
**位深**是每个采样用多少位二进制数表示。位数越多，可表示的振幅级数越细，量化噪声越低，理论动态范围越大；经验值是每增加 1 位，动态范围增加 6 dB。

CD 的 16 位理论动态范围是 96 dB；24 位是 144 dB，超过大多数录音环境的本底噪声，因此给录音电平与后期处理留出余量。位深不决定频率上限，那是采样率的事。

常见误解：把位深当成音质档次，以为 24 位一定比 16 位好听。回放时 16 位已覆盖正常聆听的动态范围；24 位的主要价值在录制与混音阶段，以及减少反复处理带来的累积误差。

相关 → [[glossary:sample-rate]]
:::

::: en
**Bit depth** is the number of binary bits used for each sample. More bits give finer amplitude steps, a lower quantization noise floor and a wider theoretical dynamic range; the rule of thumb is 6 dB more range for each added bit.

CD audio at 16 bits has a theoretical dynamic range of 96 dB. At 24 bits it is 144 dB, beyond the noise floor of most recording rooms, which leaves headroom for recording levels and later processing. Bit depth does not set the frequency ceiling; that is the job of sample rate.

The usual mistake is to treat bit depth as a quality grade and assume 24 bits always sounds better than 16. For playback, 16 bits already covers the dynamic range of normal listening. The main value of 24 bits is during recording and mixing, and in reducing accumulated error across repeated processing.

Related → [[glossary:sample-rate]]
:::
