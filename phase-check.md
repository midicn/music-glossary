---
id: phase-check
site: gloss
cat: G7
title: 相位检查
title_en: Phase Check
summary: 核对多路信号叠加是否抵消，避免梳状滤波
summary_en: Checking whether combined signals cancel, causing comb filtering and a thin sound
level: brief
tags: [混音, 相位, 检查]
tags_en: [mixing, phase, checking]
alias: [相位检查, phase check, 相位核对, 极性检查]
order: 555
links:
  - "[[glossary:mixdown]]"
  - "[[glossary:monitoring]]"
  - "[[glossary:headphone-mix]]"
sources:
  - 多麦克风相位与单声道校验，参 Huber & Runstein, Modern Recording Techniques 与 Bobby Owsinski, The Mixing Engineer's Handbook；本文为原创表述
updated: 2026-10-28
---

::: zh
**相位检查（phase check）** 是核对多路信号叠加时是否相互增强或抵消的步骤。两支麦克风录同一件乐器、立体声对、叠加的鼓样本，都可能因时间差产生梳状滤波，让某些频率变薄。

常用手段是单声道折叠、相关性表、极性反转与逐轨独听：单声道下明显变薄或消失，说明存在抵消；极性反转若让低频变实，原极性可能接反。时间对齐比单纯反转更根本。

常见误解是把相位问题一律「修掉」。立体声的宽度本身依赖左右差异；该保留的相位差要保留，只在抵消损害音色时处理。
:::

::: en
A **phase check** verifies whether combined signals reinforce or cancel each other. Two microphones on one instrument, a stereo pair, or layered drum samples can produce comb filtering from small time differences, thinning certain frequencies.

Useful tools are the mono fold-down, a correlation meter, polarity inversion and soloing each source. If the sound thins or vanishes in mono, cancellation is present; if inverting polarity restores low end, the original polarity may be reversed. Time alignment is more fundamental than a simple flip.

The usual mistake is fixing every phase difference. Stereo width depends on differences between left and right; keep the phase relationships that serve the sound and treat only the cancellations that damage it.
:::
