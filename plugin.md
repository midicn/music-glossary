---
id: plugin
site: gloss
cat: G7
title: 插件
title_en: Plug-in
summary: 在宿主里运行的效果器或乐器软件模块
summary_en: A software effect or instrument module that runs inside a host
level: brief
tags: [制作, 软件, 效果器]
tags_en: [production, software, plugin]
alias: [插件, plug-in, plugin, 效果器插件, 虚拟乐器]
order: 538
links:
  - "[[glossary:daw]]"
  - "[[glossary:latency]]"
  - "[[glossary:sampler]]"
sources:
  - 插件格式与宿主关系，参 Huber & Runstein, Modern Recording Techniques 与通行 DAW 文档；本文为原创表述
updated: 2026-10-28
---

::: zh
**插件（plug-in）** 是运行在宿主（DAW）里的软件模块，分效果器与虚拟乐器两类：均衡、压缩、混响、合成器、采样器都以插件形式加载。常见格式有 VST、AU、AAX，格式与平台并不通用，购买前要确认宿主支持。

插件不是独立程序：它借用宿主的音频流、时钟与自动化，工程保存的是参数状态，不是音频。插件可能带来延迟与 CPU 开销，多个重插件叠加会让缓冲区吃紧；混音时可以用冻结或渲染成音频来减负。

常见误解是插件越多，声音越专业。插件只是工具，决定结果的是听辨与判断；同一款插件在不同电平、不同素材上差别很大。

相关 → [[glossary:daw]]
:::

::: en
A **plug-in** is a software module that runs inside a host DAW, either an effect or a virtual instrument: EQ, compression, reverb, synthesizers and samplers all load as plug-ins. Common formats are VST, AU and AAX, which are not interchangeable, so check host support before buying.

A plug-in is not a standalone program: it uses the host's audio stream, clock and automation, and the project stores its parameter state rather than audio. Plug-ins can add latency and CPU cost, and stacking several heavy ones strains the buffer; freezing or rendering to audio lightens the load.

The usual mistake is to assume more plug-ins make a sound more professional. They are tools; listening and judgement decide the result, and the same plug-in behaves differently at different levels and on different material.

Related → [[glossary:daw]]
:::
