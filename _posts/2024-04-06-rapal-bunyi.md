---
title: "studi rapal bunyi"
date: 2024-04-06
last_modified_at: 2026-06-04
header:
  teaser: /assets/images/blog/rapalbunyi.jpg
methods:
  - generative patch
  - open sound control
  - interactive
tools:
  - wiimote
  - osculator
  - modular synth
categories:
  - project
tags:
  - jamming
  - electronic music
  - interactive
excerpt: jamming/study on wiimote controlling eurorack parameter.
---

{% include video id="xURqaCqTq1A" provider="youtube" %}

i’m using Osculator app to receive signal from wiimote and translate it into midi. and then passing it thru Midi Patchbay (an open source app to patch between midi devices without midi host) to Ornament & Crime module, using Captain Midi app to convert midi to cv.

Osculator is a great app to connect various devices for interactive applications. but unfortunately, at the time of this writing the latest compatibility is only up until macOS Big Sur. that’s why i’m using my old macbookpro 2011.

### patch notes

* i’m sending 4 midi cc from osculator to OC, convert it into 4 cv. 
* use it to control almost all parameters of mutable Rings. 
* from one of the Ring’s output, i patch it into Delay No More, which also get cv input from OC.
* the bass sound come from tonestar2600, with modulation input into cutoff filter, pwm, lfo speed.
