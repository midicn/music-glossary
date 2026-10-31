---
id: return
site: gloss
cat: G7
title: 返回
title_en: Return
summary: 接收发送来的信号，处理后混回主输出的效果通道
summary_en: The effects channel that receives sends and blends their processed signal back into the mix
level: brief
tags: [制作, 混音, 效果]
tags_en: [production, mixing, effects]
alias: [返回, return, 返回通道, 效果返回]
links:
  - "[[glossary:send]]"
  - "[[glossary:bus]]"
  - "[[glossary:reverb]]"
sources:
  - 效果返回通道的作用与共享方式，参 Bobby Owsinski, The Mixing Engineer's Handbook 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-10-28
---

::: zh
**返回（return）** 是接收发送信号、把湿声混回主输出的通道。它通常自带推子、声像与 EQ，一条返回可以服务多个发送——所有送入同一混响的轨道共享这个空间。

返回上的效果器一般设为全湿声，干声由原通道直达，两者在总线汇合。返回推子决定整体湿度：推高返回，等于同时加深所有送入的乐器。

常见误解是每条发送都要配一条返回。返回是共享资源，需要不同设置时再分设第二条；否则只会让混音更难控制，空间处理见 [[glossary:reverb]]。
:::

::: en
**A return** is the channel that receives a send and blends the processed wet signal back into the mix. It normally has its own fader, pan and EQ, and one return can serve many sends: every track feeding the same reverb shares that space.

Effects on a return are usually set to 100 percent wet, because the dry sound arrives directly from its own channel and the two meet at the bus. The return fader sets the overall wet level: raising it deepens the effect for every instrument sent there.

The usual mistake is to assume each send needs its own return. A return is a shared resource; add a second one only when the settings must differ, otherwise the mix becomes harder to control.
:::
