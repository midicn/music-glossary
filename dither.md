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
updated: 2026-10-28
---

::: zh
**抖动（dither）** 是在降低位深之前加入极低电平的噪声，让量化误差不再与信号相关。把 24 位降到 16 位时，最低几个比特被舍去；若直接截断，弱音与混响尾巴会出现砂纸般的颗粒失真，dither 把它换成均匀的细噪。

它不能恢复已丢失的细节，只是让损失听起来更自然，代价是极轻的噪声底。母带交付 16 位 CD 或某些有损编码前通常做一次；24 位工程内部反复加 dither 没有意义。噪声整形可以把噪声往人耳不敏感的高频推。

常见误解是 dither 能提升分辨率，或者多抖几次更保险。它只在最终降位深时加一次；在 24 位或浮点工程里加，只是增加噪声。

相关 → [[glossary:bit-depth]]
:::

::: en
**Dither** is very low-level noise added before reducing bit depth, so quantization error no longer correlates with the signal. Going from 24-bit to 16-bit discards the lowest bits; truncating directly leaves gritty distortion on quiet passages and reverb tails, while dither turns it into even hiss.

It cannot restore lost detail; it only makes the loss sound more natural, at the cost of a slightly higher noise floor. Mastering applies it once when delivering 16-bit CD audio or certain lossy encodes; repeating it in a 24-bit project makes no sense. Noise shaping pushes the noise toward less sensitive highs.

The usual mistake is to think dither adds resolution, or that several passes are safer. It belongs once, at the final bit-depth reduction; in a 24-bit or floating-point project it only adds noise.

Related → [[glossary:bit-depth]]
:::
