---
id: limiter
site: gloss
cat: G7
title: 限制器
title_en: Limiter
summary: 把峰值压在阈值以下，防止削波
summary_en: Holding peaks below a threshold to prevent clipping
level: brief
tags: [制作, 动态, 母带]
tags_en: [production, dynamics, mastering]
alias: [限制器, limiter, 限幅器, 峰值限制]
order: 1983
links:
  - "[[glossary:compressor]]"
  - "[[glossary:true-peak-limiter]]"
  - "[[glossary:lufs]]"
sources:
  - 限制器的参数与母带用法，参通行录音教材；本文为原创表述
updated: 2026-10-28
---

::: zh
**限制器（limiter）** 把超过**阈值**的峰值压下去，通常用极高比率与**前瞻**（lookahead）来保证输出不削波。它是母带链的最后一道保险。

它和**压缩器**不同：压缩器用于塑造动态，限制器用于**兜住峰值**；它和**最大化器**也不同：限制器保真，最大化器常为响度牺牲更多。**常见误解是「限制器越狠越响越好」**——压得太狠会失去瞬态与呼吸；**限制器是保险，不是音色。**

深入阅读 → [[glossary:compressor]]
:::

::: en
**A limiter** holds peaks above a **threshold** down, usually with a very high ratio and **lookahead**, so the output does not clip. It is the last safety stage in a master chain.

It differs from a **compressor**: a compressor shapes dynamics, a limiter **catches peaks**; it differs from a **maximizer** too: a limiter aims at fidelity, a maximizer often trades more for loudness. **The usual mistake is to push the limiter harder for more loudness** — too much kills transients and breathing; **the limiter is insurance, not tone.**

Read deeper → [[glossary:compressor|compressor]]
:::
