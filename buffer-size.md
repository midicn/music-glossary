---
id: buffer-size
site: gloss
cat: G7
title: 缓冲区
title_en: Buffer Size
summary: 一次处理的采样块大小，决定延迟与 CPU 负担
summary_en: The block of samples processed at once, trading latency against CPU load
level: brief
tags: [制作, 音频接口, 延迟]
tags_en: [production, audio interface, latency]
alias: [缓冲区, buffer size, 缓冲大小, 音频缓冲]
order: 537
links:
  - "[[glossary:latency]]"
  - "[[glossary:daw]]"
  - "[[glossary:sample-rate]]"
sources:
  - 缓冲区与延迟的换算，参 Huber & Runstein, Modern Recording Techniques 与通行音频接口说明
updated: 2026-10-28
---

::: zh
**缓冲区（buffer size）** 是音频接口一次交给电脑处理的采样块大小，通常以采样数表示：64、128、256、512、1024。它直接换算成延迟——44.1 kHz 下 128 个采样约为 2.9 毫秒，这还是单程；实际还要加上转换与驱动开销，往返会更大。

小缓冲区适合录音与演奏，响应快，但 CPU 压力大；大缓冲区适合混音与母带，负载稳，但监听会拖。爆音、咔嗒声常常不是设备坏，而是缓冲区太小、插件太重。**通行做法**是录音时降到 64–128，混音时升到 512–1024。

常见误解是缓冲区会影响音质。它改变的是处理节奏与延迟，不改变采样率与位深；同一工程换缓冲区，导出的音频应当一致。

相关 → [[glossary:latency]]
:::

::: en
**Buffer size** is the block of samples an audio interface hands to the computer at a time, usually in samples: 64, 128, 256, 512 or 1024. It converts directly into latency — at 44.1 kHz, 128 samples is about 2.9 ms one way — before converter and driver overhead.

A small buffer suits recording and performing: quick response, more CPU work. A large buffer suits mixing and mastering: stable load, sluggish monitoring. Clicks and dropouts are often not a broken device but a buffer too small for the plug-ins in use. The common practice is 64–128 while tracking and 512–1024 while mixing.

The usual mistake is to expect buffer size to change sound quality. It changes processing rhythm and latency, not sample rate or bit depth; the same project should export identically at any buffer size.

Related → [[glossary:latency]]
:::
