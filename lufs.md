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
  - LUFS 的加权与门限算法，参 ITU-R BS.1770-4（2015）；平台目标值参 EBU R 128 与各平台公开的响度归一化说明；本文为原创表述
updated: 2026-10-28
---

::: zh
**LUFS**（Loudness Units relative to Full Scale）是测量感知响度的单位，算法依据 ITU-R BS.1770：先按频率与声道能量加权，再做时间门限统计。它描述整段节目的平均响度，不是瞬时峰值。

平台会按自己的目标值统一上传母带的响度：Spotify 默认以 -14 LUFS 归一化，Apple Music 以 -16 LUFS 为目标，EBU R128 广播为 -23 LUFS。母带做得更响，平台会把它整体压下来；靠限幅换来的响度并不会留下更多动态。

常见误解：把 LUFS 当成音量旋钮或峰值表。LUFS 是节目整体响度，峰值要看 dBTP；两者不是同一刻度。混音时先看 LUFS 是否合目标，再看 true peak 是否超过 0 dBTP。

相关 → [[glossary:daw]]
:::

::: en
**LUFS** (Loudness Units relative to Full Scale) measures perceived loudness. Its algorithm follows ITU-R BS.1770: frequency and channel energy are weighted, then gated over time. It describes the average loudness of a whole programme, not an instantaneous peak.

Platforms normalize uploaded masters to their own targets: Spotify normalizes to -14 LUFS by default, Apple Music targets -16 LUFS, and EBU R128 broadcast uses -23 LUFS. A louder master is turned down as a whole; loudness gained through limiting does not leave more dynamics.

The usual mistake is to treat LUFS as a volume knob or a peak meter. LUFS measures overall programme loudness; peaks are read in dBTP. They are different scales. When mixing, check LUFS against the target first, then check whether true peak exceeds 0 dBTP.

Related → [[glossary:daw]]
:::
