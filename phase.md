---
id: phase
site: gloss
cat: G7
title: 相位
title_en: Phase
summary: 同一波形在时间上的相对位置
summary_en: The relative position in time of one waveform against another
level: brief
tags: [声学, 混音, 时间]
tags_en: [acoustics, mixing, timing]
alias: [相位, phase, 相位差, 相移]
links:
  - "[[glossary:phase-check]]"
  - "[[glossary:comb-filtering]]"
  - "[[glossary:stereo-technique]]"
sources:
  - 相位与多麦克风叠加，参 Huber & Runstein, Modern Recording Techniques 与 Bobby Owsinski, The Mixing Engineer's Handbook
updated: 2026-10-28
---

::: zh
**相位（phase）** 描述周期性波形在时间上的相对位置，常用角度或时间差表示。两个同频信号若波峰对齐就同相叠加，错开半个周期则相互抵消；不同频率的相位差对应的实际时间并不相同。

录音里，相位差来自麦克风间距、声源到各麦的路径差，以及延迟与滤波电路。多支麦录同一来源时，相位差会让某些频率增强、某些减弱，形成梳状滤波；单声道折叠与相关性表可以用来判断。

常见误解是把相位与极性混为一谈。极性反转只是把波形上下翻转，相当于 180 度；相位是连续的时间关系，不能靠一个开关全部解决。
:::

::: en
**Phase** describes where one periodic waveform sits in time relative to another, expressed as an angle or a delay. Two signals at the same frequency add when their peaks align and cancel when displaced by half a cycle; the same phase offset means different time shifts at different frequencies.

In recording, phase differences come from microphone spacing, path length from source to each mic, and delays or filters. When several mics hear one source, those differences boost some frequencies and weaken others, producing comb filtering; a mono fold-down and a correlation meter help reveal it.

The usual mistake is confusing phase with polarity. Flipping polarity turns the waveform upside down, equivalent to 180 degrees; phase is a continuous timing relationship and no single switch resolves it.
:::
