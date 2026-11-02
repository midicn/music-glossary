---
id: dither
site: gloss
cat: G7
title: 抖动
title_en: Dither
summary: 降低位深前加入微量噪声，把量化误差变成细噪
summary_en: Adding a tiny amount of noise before bit-depth reduction so quantization error becomes noise
level: brief
tags: [母带, 位深, 噪声]
tags_en: [mastering, bit depth, noise]
alias: [抖动, dither, 抖动噪声, 抖动处理]
order: 535
links:
  - "[[glossary:bit-depth]]"
  - "[[glossary:mastering]]"
  - "[[glossary:sample-rate]]"
sources:
  - 抖动与噪声整形，参 Bob Katz, Mastering Audio 与通行母带教材
  - https://prod.fabfilter.com/help/pro-l/using/dithering
updated: 2026-11-03
---

::: zh
**抖动（dither）**是在量化为较低的整数位深前加入低电平噪声，使量化失真变为较均匀的噪声。它不恢复已经丢失的信息，也不保证听感一定改善。

常见用途是最终把高精度母带导出为16位PCM；从浮点转为24位整数时，也应根据交付位深与处理链判断。按目标位深设置，放在最终量化步骤，避免插件与导出器重复加抖动。噪声整形改变噪声的频谱分布。

AAC、MP3不采用固定的PCM位深，不能因“有损”就照搬16位抖动流程。先保留高质量母带，再按交付要求编码。

相关 → [[glossary:bit-depth]]
:::

::: en
**Dither** is low-level noise added before quantization to a lower integer bit depth. It trades signal-dependent quantization distortion for a noise floor; it neither restores lost information nor guarantees an audible improvement.

A typical use is final export to 16-bit PCM. Float-to-24-bit export also requires a decision about the target and processing chain. Match the target bit depth and avoid duplicate dither in the plug-in and exporter. Noise shaping redistributes the noise spectrum.

AAC and MP3 do not use a fixed PCM bit depth. Lossy encoding alone is not a reason to add 16-bit dither.

Related → [[glossary:bit-depth]]
:::
