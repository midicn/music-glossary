---
id: send
site: gloss
cat: G7
title: 发送
title_en: Send
summary: 把信号分出一路送往效果总线，原轨仍直达输出
summary_en: A split of a channel's signal sent to an effects bus while the dry path still reaches the output
level: brief
tags: [制作, 混音, 路由]
tags_en: [production, mixing, routing]
alias: [发送, send, 送出, 效果发送]
links:
  - "[[glossary:bus]]"
  - "[[glossary:return]]"
  - "[[glossary:reverb]]"
sources:
  - 发送与返回的路由及推子前/后用法，参 Bobby Owsinski, The Mixing Engineer's Handbook 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-10-28
---

::: zh
**发送（send）** 从通道里分出一路信号，送往效果总线、监听或录音机。它与插入不同，原信号仍沿主路径直达输出，分出的这一路有独立电平。

发送分推子前与推子后：推子前不受通道推子影响，常用于独立监听；推子后随推子升降，效果量才能跟住音乐。发送通常成对出现：送出到总线，再由返回混回来。

常见误解是把发送当成效果器本身。发送只负责路由与电平，声音处理发生在目的地；湿声比例由发送量与返回量共同决定，用法见 [[glossary:reverb]]。
:::

::: en
**A send** taps a channel's signal and routes a copy to another destination: an effects bus, a cue mix or a recorder. Unlike an insert, the original signal still travels its main path to the output, while the tapped copy has its own level.

Sends are pre-fader or post-fader. A pre-fader send ignores the channel fader and suits independent monitoring; a post-fader send follows the fader, so the effect tracks the music. Sends usually work in pairs: out to a bus, back through a return.

The usual mistake is to treat a send as an effect. It is only routing and level; the processing happens at the destination, and the wet amount depends on both the send and the return.
:::
