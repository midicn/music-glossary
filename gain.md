---
id: gain
site: gloss
cat: G7
title: 增益
title_en: Gain
summary: 对信号电平的整体放大或衰减，是信号链的基本量
summary_en: Overall boost or cut of a signal's level, the basic quantity of any signal chain
level: brief
tags: [制作, 电平, 基础]
tags_en: [production, level, basics]
alias: [增益, gain, 电平增益, 放大]
links:
  - "[[glossary:gain-staging]]"
  - "[[glossary:headroom]]"
  - "[[glossary:clipping]]"
sources:
  - 增益与电平结构，参 Bob Katz, Mastering Audio 与 Huber & Runstein, Modern Recording Techniques；本文为原创表述
updated: 2026-10-28
---

::: zh
**增益（gain）** 是对信号电平的整体放大或衰减，用分贝表示。它发生在信号链的某一级：话筒放大器、插件输入、总线输出，每一级的增益都会叠加。

增益与音量推子并不相同：增益通常加在输入端，会改变进入效果器的电平，甚至改变失真与压缩的行为；推子多在输出端，只改听到的响度。

常见误解是增益就是音量。推高增益会让后续处理收到更热的信号，可能削波；做法是每级留余量，把响度留给最后，具体可参 [[glossary:gain-staging]]。
:::

::: en
**Gain** is an overall boost or cut of a signal's level, measured in decibels. It happens at one stage of the chain: a preamp, a plug-in input, a bus output, and every stage adds to the total.

Gain and a volume fader are not quite the same. Gain usually sits at the input and changes the level entering processors, which can alter distortion and compression behavior; a fader usually sits at the output and changes only how loud the result is.

The usual mistake is to treat gain as volume. Pushing gain feeds later stages a hotter signal and can clip; the better habit is to leave headroom at each stage and save loudness for the end.
:::
