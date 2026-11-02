---
id: velocity
site: gloss
cat: G7
title: MIDI 力度值
title_en: MIDI Velocity
summary: 音符的击键强度值，由音源决定它变成什么
summary_en: The strike-strength value of a MIDI note; the sound source decides what it becomes
level: brief
tags: [MIDI, 力度, 制作]
tags_en: [midi, velocity, production]
alias: [力度值, 击键速度, MIDI velocity, note velocity]
order: 155
links:
  - "[[glossary:midi-protocol]]"
  - "[[glossary:daw]]"
  - "[[concept:timbre]]"
sources:
  - MIDI 力度值的 7 位范围、note on/off 语义与 MIDI 2.0 的扩展，参 MIDI 1.0 Specification 与 MIDI 2.0 Specification（MMA）
  - https://midi.org/summary-of-midi-1-0-messages
  - https://midi.org/about-midi-part-3midi-messages
updated: 2026-11-03
---

::: zh
**velocity** 是 MIDI 音符消息里的击键强度值，范围 0–127。音符开（note on）带一个 velocity，音符关（note off）也带一个 release velocity；在MIDI 1.0中，力度为0的note on按note off处理。

它不是音量本身，而是一个输入值。音源可以把它映射到振幅，也可以映射到滤波器截止、采样层切换或包络速度；同样的力度值在钢琴音源和弦乐音源上效果不同。MIDI 2.0 把力度扩展到 16 位。

常见误解：velocity 等于音量。把力度画成一条起伏的曲线，只改变了输入值；即使没有多层采样，音源仍可用力度连续控制音量或音色；若音色设置为忽略力度，改变数值才可能听不出差别。应检查音源的力度响应设置。

相关 → [[glossary:midi-protocol]]
:::

::: en
**Velocity** is the strike-strength value carried in a MIDI note message, ranging from 0 to 127. A note-on message carries one velocity and a note-off message carries a release velocity; in MIDI 1.0, a note-on with velocity 0 is treated as note-off.

It is not volume itself but an input value. A sound source may map it to amplitude, filter cutoff, sample-layer selection or envelope speed, so the same value behaves differently on a piano and on a string patch. MIDI 2.0 extends velocity to 16 bits.

The usual mistake is to equate velocity with volume. Drawing a rising and falling velocity curve only changes the input value; even without sample layers, velocity can continuously control amplitude or timbre. A patch set to ignore velocity may show little audible change. Check its velocity-response settings rather than assuming that layering is required.

Related → [[glossary:midi-protocol]]
:::
