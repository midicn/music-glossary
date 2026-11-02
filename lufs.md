---
id: lufs
site: gloss
cat: G7
title: LUFS 响度单位
title_en: LUFS (Loudness Units relative to Full Scale)
summary: 按人耳感知加权的响度单位，流媒体各有目标值
summary_en: A perceptually weighted loudness unit, with different targets on streaming platforms
level: brief
tags: [响度, 母带, 制作]
tags_en: [loudness, mastering, production]
alias: [LUFS, LKFS, 响度单位, loudness units full scale]
order: 154
links:
  - "[[glossary:daw]]"
  - "[[glossary:sidechain]]"
sources:
  - LUFS 的加权与门限算法，参 ITU-R BS.1770-4（2015）；平台目标值参 EBU R 128 与各平台公开的响度归一化说明
  - https://tech.ebu.ch/files/live/sites/tech/files/shared/tech/tech3341v4_0.pdf
  - https://support.spotify.com/au/artists/article/loudness-normalization/
updated: 2026-11-03
---

::: zh
**LUFS**（Loudness Units relative to Full Scale）是以数字满刻度为参考的响度单位。基于ITU-R BS.1770的测量使用频率与声道加权；它与峰值电平不是同一指标。

读数还须注明时间尺度：**M**为约400毫秒的瞬时响度，**S**为3秒的短时响度，**I**为所选节目范围的综合响度。综合测量使用门限，不能把它当作所有采样值的简单平均。

流媒体播放归一化取决于平台、设备、用户设置与专辑模式。Spotify的Normal模式以约−14 LUFS为参考，但这不是所有平台的统一交付标准；峰值余量也可能限制可提升的增益。交付时分别核对综合响度、真峰值上限及实际听感，不要只追一个LUFS数字。

相关 → [[glossary:true-peak]]
:::

::: en
**LUFS** measures loudness relative to digital full scale. BS.1770-based measurement uses frequency and channel weighting; loudness and peak level are different measurements.

Specify the timescale: **M** is momentary loudness over about 400 ms, **S** is short-term loudness over 3 seconds, and **I** is integrated loudness over the chosen programme. Integrated measurement uses gating rather than simply averaging every sample.

Playback normalization depends on service, device, user setting and album mode. Spotify Normal uses about −14 LUFS as a reference, not a universal delivery requirement; peak headroom can limit gain increases. Check integrated loudness and true-peak limits separately against the actual delivery specification, then listen.

Related → [[glossary:true-peak]]
:::
