---
title: MUSIC-PRODUCTION <i class="fa-solid fa-radio"></i><i class="fa-solid fa-music"></i>
permalink: /music-production/
excerpt: >
  songs & stages.<br />
  <a>*archives of my music production journey through out the years.*</a><br />
  <small>for scoring-works check out the link below.</small>
header:
  overlay_image: /assets/images/banner/lee-wall-banner-flip.webp
  overlay_filter: 0.16
  actions:
    - label: "<i class='fa-solid fa-photo-film'></i> Scoring-Works"
      url: "/scoring-works/"
toc: true
toc_sticky: true
toc_label: 'portfolio'
toc_icon: 'clapperboard'
categories:
  - portfolio
tags:
  - music production
---

## S t u d i o <i class="fa-solid fa-microphone-lines"></i>
{: #studio }

### \producer-arranger
*songs and albums that i produced, arranged, and mixed.*

#### >> various-artist
{: #various-artist-studio }
<div class="music-production-grid">
{% for item in site.data.music-production.songs %}
  <div class="music-production-item">
        <a href="{{ item.url | relative_url }}">
          <img
            src="{{ item.image_path | relative_url }}"
            alt="{{ item.alt }}">
        </a>
        <p>
          <a href="{{ item.url | relative_url }}" class="music-production-title">
            {{ item.title }}
          </a>
          <br>
          <span class="music-production-alt">
          {{ item.alt}}
          </span>
        </p>
  </div>
{% endfor %}
</div>

---

#### >> andien - melodi monolog
<div class="video-gallery__item">
    {% include video-thumb.html
       id="NrTJBIFhVk4" 
    %}
</div>

---

#### >> spotify playlist
*the essential tracks, all in one playlist.*
<iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1DZ06evO0lD8fN?utm_source=generator" width="100%" height="450" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

---

#### >> soundtrack
<div class="music-production-grid">
{% for item in site.data.music-production.ost %}
  <div class="music-production-item">
        <a href="{{ item.url | relative_url }}">
          <img
            src="{{ item.image_path | relative_url }}"
            alt="{{ item.alt }}">
        </a>
        <p>
          <a href="{{ item.url | relative_url }}" class="music-production-title">
            {{ item.title }}
          </a>
          <br>
          <span class="music-production-alt">
          {{ item.alt}}
          </span>
        </p>
  </div>
{% endfor %}
</div>

---

## L i v e <i class="fa-solid fa-drum"></i>
{: #live }

### \concerts
*had been an honor to work as music director for these concerts.*

#### >> various-artist
<div class="music-production-grid">
{% for item in site.data.music-production.concert %}
  <div class="music-production-item">
        <a href="{{ item.url | relative_url }}">
          <img
            src="{{ item.image_path | relative_url }}"
            alt="{{ item.alt }}">
        </a>
        <p>
          <a href="{{ item.url | relative_url }}" class="music-production-title">
            {{ item.title }}
          </a>
          <br>
          <span class="music-production-alt">
          {{ item.alt}}
          </span>
        </p>
  </div>
{% endfor %}
</div>

---

### \stages
{: .text-left}
*composing and arranging music for theater production. occasionally conduct the orchestra too.*

#### >> various-production
{: #various-artist-live }
<div class="music-production-grid">
{% for item in site.data.music-production.theater %}
  <div class="music-production-item">
        <a href="{{ item.url | relative_url }}">
          <img
            src="{{ item.image_path | relative_url }}"
            alt="{{ item.alt }}">
        </a>
        <p>
          <a href="{{ item.url | relative_url }}" class="music-production-title">
            {{ item.title }}
          </a>
          <br>
          <span class="music-production-alt">
          {{ item.alt}}
          </span>
        </p>
  </div>
{% endfor %}
</div>

---
#### >> jayaprana-layonsari
<div class="video-gallery__item">
    {% include video-thumb.html
       id="mU311AVgJkU"
      %}
  </div>

---