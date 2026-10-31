---
id: de-esser
site: gloss
cat: G7
title: 齿音消除器
title_en: De-esser
summary: 专门压掉人声里刺耳的齿音，常用高频动态处理
summary_en: A processor that tames harsh sibilance in vocals, usually by dynamic high-frequency control
level: brief
tags: [制作, 人声, 动态]
tags_en: [production, vocal, dynamics]
alias: [齿音消除器, de-esser, deesser, 去齿音]
links:
  - "[[glossary:compressor]]"
  - "[[glossary:eq]]"
  - "[[glossary:dynamic-eq]]"
sources:
  - 齿音消除的频率范围与分频方式，参 Bobby Owsinski, The Mixing Engineer's Handbook 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-10-28
---

::: zh
**齿音消除器（de-esser）** 专门对付人声里的齿音：s、sh、z 这类辅音能量集中高频，听久了刺耳。它检测到齿音时快速压低那一小段，其他时间不介入。

分频式只压高频段，宽带式会整体轻压；前者更透明，后者更自然但会影响音色。阈值与频率要对准歌手的发声，过量会让字头变成「大舌头」。

常见误解是用静态 EQ 切掉高频。齿音是间歇的，静态衰减会连明亮感一起拿走；动态处理只在该出现时出现，压缩基础见 [[glossary:compressor]]。
:::

::: en
**A de-esser** targets sibilance in vocals: the energy of s, sh and z consonants gathers in the high frequencies and turns harsh over time. When it detects a sibilant, it turns that narrow range down quickly and stays out of the way otherwise.

Split-band designs compress only the high range; wideband designs duck the whole signal slightly. The first is more transparent, the second can sound more natural but colors the tone. Set threshold and frequency around the singer's voice, because too much correction gives a lisp.

The usual mistake is to cut the highs with a static EQ. Sibilance is intermittent, so a fixed cut removes brightness everywhere; dynamic control acts only when the problem appears.
:::
