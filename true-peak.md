---
id: true-peak
site: gloss
cat: G7
title: 真峰值
title_en: True Peak
summary: 重建波形后的峰值，用 dBTP 表示，常留 1 dB 余量
summary_en: The peak of the reconstructed waveform, read in dBTP with a little ceiling margin
level: brief
tags: [母带, 峰值, 响度]
tags_en: [mastering, peak, loudness]
alias: [真峰值, true peak, 采样间峰值, dBTP]
order: 554
links:
  - "[[glossary:clipping]]"
  - "[[glossary:lufs]]"
  - "[[glossary:loudness-war]]"
sources:
  - 真峰值测量与上限设置，参 Bob Katz, Mastering Audio 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-10-28
---

::: zh
**真峰值（true peak）** 是重建连续波形后得到的峰值，而不是采样点上的最大值。数模转换会把采样点连成平滑曲线，曲线可能越过相邻样本，形成采样间峰值。

它以 dBTP 表示，按 ITU-R BS.1770 与 EBU R128 的方法用数倍过采样估算。母带常把上限设在 -1 dBTP 左右，给有损编码留余量；限制器若只看样本峰值，导出后仍可能削波。

常见误解是采样峰值不超 0 dBFS 就安全。转换器与编解码器会在采样之间插值，真峰值超限照样失真；看表时要认准 dBTP 而不是 dBFS。
:::

::: en
**True peak** is the peak of the reconstructed continuous waveform, not the highest sample value. Conversion joins samples into a smooth curve, and that curve can rise above the neighbouring samples, creating an inter-sample peak.

It is expressed in dBTP and estimated with several times oversampling, following the methods of ITU-R BS.1770 and EBU R128. Masters often set the ceiling near -1 dBTP to leave room for lossy encoding; a limiter watching only sample peaks may still clip after export.

The usual mistake is assuming a sample peak below 0 dBFS is safe. Converters and codecs interpolate between samples, so a true peak over the ceiling distorts just the same. Read dBTP, not dBFS.
:::
