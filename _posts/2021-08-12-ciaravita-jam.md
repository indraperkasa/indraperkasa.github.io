---
title: "//ciaravita - a Crow Druid Jam"
date: 2021-08-21
last_modified_at: 2026-06-04
header:
  teaser: /assets/images/blog/ciaravita-jam.jpg
platforms:
  - monome
  - mannequins
devices:
  - crow
  - mangrove
  - three-sisters
  - wslash
  - just-friends
  - cold-mac
categories:
  - project
moods:
  - ambient
  - floating
tags:
  - jamming
  - electronic music
  - modular synth
  - coding
  - lua
  - druid
excerpt: semi live coding monome crow using druid.
---

{% include video id="P4xMkBWlstA" provider="youtube" %}

i was studying [Crow](https://monome.org/docs/crow/) v3 new feature, sequins. a very powerful sequencing tools, and yet so simple. the idea of nested sequencing, building up complex structure out of the simple ones, and use that literally to sequence/modulate anything is absolutely amazing. need to dig deeper about this.

i was learning coding in [druid](https://monome.org/docs/crow/druid/) from the master `Trent's Maps season 2`:
{% include video id="WQyoDRRQ5Qg" provider="youtube" %}

---

**Patch Notes**

* the sound source featuring: 
  * [Mannequins W/](https://www.whimsicalraps.com/products/wslash) in Synth mode, using the latest beta firmware, and 
  * [Mangrove](https://www.whimsicalraps.com/products/mangrove) as bass/low melody.

* i routed the W/ synth thru [Three Sisters](https://www.whimsicalraps.com/products/sisters) low and high, 
* then to [Cold Mac](https://www.whimsicalraps.com/products/cold-mac) left and right input, with lfo from [Just Friends](https://www.whimsicalraps.com/products/just-friends) to fade input, to get the crossing panning animation. 
* then **Mangrove** format output to **Cold Mac** offset input,  so it stays in the center panning. 
* did a little bit of feedback patch on **Mangrove** to get a little bit tone variation. 
* **Mangrove** square out to **Cold Mac** *OR*'s input, with *OR2* input is lfo from **Just Friends**. 
* *OR* out to *CREASE* in. 
* and then i take output of *CREASE* to *FM* input of *Mangrove*.
* stereo out from modular then goes to mixer, 
* add reverb-delay spacetime from **H9** pedal.
* record stereo out to **DAW**, and do a little bit of 'mastering'.

i released the track on bandcamp. check it out [here]({% post_url 2021-08-12-binary-dance-single %}).