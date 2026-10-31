---
id: midi-protocol
site: gloss
cat: G7
title: MIDI 协议
title_en: MIDI Protocol
summary: 1983 年的演奏控制协议，传送的是指令，不是声音
summary_en: A 1983 performance-control protocol that carries instructions, not sound
level: brief
tags: [MIDI, 协议, 制作]
tags_en: [midi, protocol, production]
alias: [MIDI, MIDI 1.0, 乐器数字接口, musical instrument digital interface]
order: 151
links:
  - "[[glossary:daw]]"
  - "[[glossary:velocity]]"
  - "[[concept:pitch]]"
sources:
  - MIDI 的消息结构、通道与 7 位数值范围，参 MIDI 1.0 Specification（MMA, 1996）与 The New Grove Dictionary of Music and Musicians, "MIDI"
updated: 2026-10-28
---

::: zh
**MIDI** 是 1983 年由多家电子乐器厂商共同制定的控制协议。它传送音符开关、力度、控制器、音色切换与时钟等演奏指令，不传送音频波形；听到的声音由接收端的合成器或采样器产生。

一条 MIDI 连接可分 16 个通道，消息中的数值多为 7 位，范围 0–127。设备靠通道号判断该响应哪条消息；音序器录下的是这些消息，回放时再把它们送回音源。音高、力度与控制器各有独立的编码。

常见误解：把 MIDI 文件当成音频文件，以为它自带音质。同一个 MIDI 文件换一套音源，音色可以完全不同；它描述的是怎么演奏，而不是最终的声音。

相关 → [[glossary:velocity]]
:::

::: en
**MIDI** is a control protocol agreed in 1983 by several electronic-instrument makers. It carries performance instructions such as note on and off, velocity, controllers, program changes and clock, but no audio waveform. The sound you hear is produced by the receiving synthesizer or sampler.

One MIDI connection can carry 16 channels, and most message values are 7-bit, from 0 to 127. Devices use the channel number to decide which messages to answer. A sequencer records these messages and sends them back to a sound source on playback; pitch, velocity and controllers each have their own encoding.

The usual mistake is to treat a MIDI file as an audio file and assume it has a sound quality of its own. The same MIDI file can sound completely different through another sound source. It describes how to play, not the final sound.

Related → [[glossary:velocity]]
:::
