---
id: latency
site: gloss
cat: G7
title: 系统延迟
title_en: Latency
summary: 信号穿过系统所花的时间，影响演奏监听
summary_en: The time a signal takes to pass through the system, which affects monitoring
level: brief
tags: [制作, 延迟, 监听]
tags_en: [production, latency, monitoring]
alias: [延迟, latency, 系统延迟, 监听延迟]
order: 536
links:
  - "[[glossary:buffer-size]]"
  - "[[glossary:daw]]"
  - "[[glossary:plugin]]"
sources:
  - 监听延迟与往返延迟，参 Huber & Runstein, Modern Recording Techniques 与通行音频接口文档
updated: 2026-10-28
---

::: zh
**延迟（latency）** 是信号从输入到输出所花的时间：话筒到转换器、缓冲区、插件处理、再到耳机，每一段都累加。录音时它表现为听到的自己晚一点；**通行说法**是超过约 10 毫秒，多数演奏者会开始察觉，节奏与手感受影响，具体阈值因人而异。

缓冲区越小，延迟越低，但 CPU 要更频繁地处理音频，负载高时容易爆音；插件——尤其前瞻（look-ahead）插件与线性相位均衡——也会增加延迟。宿主通常用延迟补偿把各轨对齐，但录音监听仍要靠低延迟路径或直接监听。

常见误解是把它和延迟效果器混为一谈。delay 是刻意制造的回声，latency 是系统绕不开的时间差。

相关 → [[glossary:buffer-size]]
:::

::: en
**Latency** is the time a signal takes from input to output: microphone to converter, through the buffer and plug-ins, then to the headphones. Every stage adds up. When recording, it shows up as hearing yourself slightly late; the rule of thumb is that past roughly 10 ms most players notice, and timing and feel suffer. The exact threshold varies by player.

A smaller buffer lowers latency, but the CPU must handle audio more often and may crackle under load. Plug-ins add delay too, especially look-ahead processors and linear-phase EQ. Hosts compensate delay to align tracks, but monitoring still needs a low-latency path or direct monitoring.

The usual mistake is to confuse it with a delay effect. A delay deliberately creates echoes; latency is the time lag the system cannot avoid.

Related → [[glossary:buffer-size]]
:::
