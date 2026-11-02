---
id: panning
site: gloss
cat: G7
title: 声像
title_en: Panning
summary: 在立体声场里安排声音的左右位置与宽度
summary_en: Placing sounds left to right in the stereo field to set width and space
level: brief
tags: [制作, 混音, 空间]
tags_en: [production, mixing, space]
alias: [声像, panning, 声像定位, 声场定位]
links:
  - "[[glossary:mix-bus]]"
  - "[[glossary:bus]]"
  - "[[glossary:reverb]]"
sources:
  - "https://www.cs.cmu.edu/~music/icm-online/readings/panlaws/"
  - "https://www.steinberg.help/r/wavelab-elements/13.0/en/wavelab/topics/audio_montage/clips_envelopes_pan_laws_c.html?contentId=BjKrY6tfXuwoYNxO4ApsYw"
  - 声像定位与单声道兼容，参 Bobby Owsinski, The Mixing Engineer's Handbook 与 Huber & Runstein, Modern Recording Techniques
updated: 2026-11-02
---

::: zh
**声像定位（panning）**通过调整声音分配到左右声道的关系，改变它在立体声场中的位置。单声道声源的声像控制与立体声信号的平衡控制不完全相同，具体行为应看所用设备或软件。

声像移动时，音量变化与**声像法则（pan law）**有关，不能一概说整体响度不变。混音中可比较声源在左、中、右的位置，并检查移动后与其他声部的平衡。

单声道兼容还取决于左右声道的相关性和相位关系；不是所有宽声像都会抵消。涉及延迟、立体声加宽等处理时，应另做单声道检查。空间处理可参 [[glossary:reverb]]。
:::

::: en
**Panning** changes a sound’s position in a stereo field by adjusting its distribution between left and right channels. A panner for a mono source and a balance control for stereo material do not necessarily behave in the same way; check the device or software.

Level changes during a pan depend on the **pan law**, so overall loudness cannot simply be assumed constant. Compare a source at left, centre and right, checking its balance against other parts after moving it.

Mono compatibility also depends on correlation and phase between channels: not every wide image cancels in mono. Check mono separately when using delays or stereo-widening processing. See [[glossary:reverb]] for spatial processing.
:::
