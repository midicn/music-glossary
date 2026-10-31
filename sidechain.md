---
id: sidechain
site: gloss
cat: G7
title: 侧链
title_en: Sidechain
summary: 用一个信号触发另一个处理器，常用于压缩
summary_en: Using one signal to trigger a processor on another, most often a compressor
level: brief
tags: [混音, 压缩, 路由]
tags_en: [mixing, compression, routing]
alias: [侧链压缩, 旁链, sidechain, side-chain, sidechain compression]
order: 156
links:
  - "[[glossary:daw]]"
  - "[[glossary:lufs]]"
sources:
  - 侧链压缩的检测路径与常见用法，参 Bobby Owsinski, The Mixing Engineer's Handbook 与通行混音教材
updated: 2026-10-28
---

::: zh
**侧链**是一种路由方式：把信号 A 送到处理器 B 的检测输入端，让 A 的电平决定 B 对信号 C 的处理量。最常见的是侧链压缩——底鼓一响，贝斯就被压下去，为鼓让出空间。

压缩器的侧链输入可以来自同一轨道的分支，也可以来自另一条轨道。除了压缩，侧链还能触发门限、滤波器或调制；给侧链信号加滤波，就能只让某个频段触发闪避。广播里用它让音乐自动闪避解说，混音里用它整理低频。

常见误解：把侧链等同于 EDM 里明显的“抽吸”。抽吸只是压缩器在强触发下的听感结果；侧链本身是控制路径，参数轻时可以是几乎听不见的整理手段。

相关 → [[glossary:daw]]
:::

::: en
**Sidechain** is a routing method: signal A is sent to the detector input of processor B, so A's level decides how much B processes signal C. The common case is sidechain compression: when the kick hits, the bass is pushed down to make room for the drum.

A compressor's sidechain input can come from a branch of the same track or from another track. Sidechain control can also drive a gate, filter or modulation, and filtering the sidechain signal lets only one frequency range trigger the ducking. Broadcast uses it to duck music under speech; mixing uses it to tidy up the low end.

The usual mistake is to equate sidechain with the obvious pumping heard in EDM. Pumping is simply how a compressor sounds under strong triggering; sidechain itself is a control path, and with gentle settings it can be an almost inaudible housekeeping tool.

Related → [[glossary:daw]]
:::
