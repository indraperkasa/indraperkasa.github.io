---
title: SCORING-WORKS <i class="fa-solid fa-photo-film"></i><i class="fa-solid fa-music"></i>
permalink: /scoring-works/
excerpt: >
  s c r e e n s.<br />
  <a>*archives of my scoring journey through out the years.*</a><br />
  <small>for music-production check out the link below.</small>
header:
  overlay_image: /assets/images/banner/lee-wall-banner-flip.webp
  overlay_filter: 0.16
  actions:
    - label: "<i class='fa-solid fa-radio'></i> Music-Production"
      url: "/music-production/"
toc: true
toc_sticky: true
toc_label: 'portfolio'
toc_icon: 'clapperboard'
categories:
  - portfolio
tags:
  - film scoring
---

## F i l m / TV Series <i class="fa-solid fa-film"></i>
{: #film-tv }

### \composer
{: .text-left}
*scoring works as the main composer.*

<div class="filmography-grid">
{% for item in site.data.filmography.main %}
  <div class="filmography-item">
        <a href="{{ item.url | relative_url }}">
          <img
            src="{{ item.image_path | relative_url }}"
            alt="{{ item.alt }}">
        </a>
        <p>
          <a href="{{ item.url | relative_url }}" class="filmography-title">
            {{ item.title }}
          </a>
          <br>
          <span class="filmography-alt">
          {{ item.alt}}
          </span>
        </p>
  </div>
{% endfor %}
</div>

---

#### >> award and nomination <i class="fa-solid fa-award"></i>
{: #award }

| Year | Movie  | Award | Category | Result |
| ---  | ---    | ---   | ---      | ---    |
| 2020 | Mudik       | Piala Maya                    | Best Music Director | Nominated |
| 2020 | Mudik       | Festival Film Indonesia       | Best Music Director | Nominated |
| 2019 | Bebas       | Piala Maya                    | Best Music Director | Nominated |
| 2019 | Bebas       | Festival Film Indonesia       | Best Music Director | Nominated |
| 2015 | Tabula Rasa | Indonesia Film Trailer Awards | Best Music Director | Won       |
| 2014 | Tabula Rasa | Festival Film Indonesia       | Best Music Director | Nominated |

---

### \additional-music | co-composer | orchestrator
{: #additional }
{: .text-left}
*helping and working together with other composers.*

<div class="filmography-grid">
{% for item in site.data.filmography.additional %}
  <div class="filmography-item">
        <a href="{{ item.url | relative_url }}">
          <img
            src="{{ item.image_path | relative_url }}"
            alt="{{ item.alt }}">
        </a>
        <p>
          <a href="{{ item.url | relative_url }}" class="filmography-title">
            {{ item.title }}
          </a>
          <br>
          <span class="filmography-alt">
          {{ item.alt}}
          </span>
        </p>
  </div>
{% endfor %}
</div>

---

## COMMERCIALS <i class="fa-solid fa-bullhorn"></i>
{: #commercials }

### \fashion
*composing and producing music for fashion show. it was a very fun experience.*

<div class="video-gallery half">
  <div class="video-gallery__item">
    {% include video-thumb.html
       id="f_quhxyd6EI"
       title="Sapto Djojokartiko <br> Spring/Summer 2021" %}
  </div>
  <div class="video-gallery__item">
    {% include video-thumb.html
       id="sZ3Z3AqoVNE"
       title="STELLARISSA <br> for Wynn (2022)" %}
  </div>

  <div class="video-gallery__item">
    {% include video-thumb.html
       id="nwz4rvB-AQY"
       title="Sapto Djojokartiko <br> Spring/Summer 2023" %}
  </div>

  <div class="video-gallery__item">
    {% include video-thumb.html
       id="UVwkx09ujf0"
       title="Sejauh Mata Memandang <br> untuk DFK 2020" %}
  </div>
</div>

---

### \brands
*composing and producing music for commercial brands and product.*

<div class="video-gallery half">
  <div class="video-gallery__item">
    {% include video-thumb.html
      id="hEARbsZPQ9M"
      title="Miele Indonesia" %}
  </div>

  <div class="video-gallery__item">
    {% include video-thumb.html
      id="AhzgAczJCC8"
      title="Fagetti Stone" %}
  </div>

  <div class="video-gallery__item">
    {% include video-thumb.html
      id="76BBh2kItXg"
      title="Telkomsel" %}
  </div>

  <div class="video-gallery__item">
    {% include video-thumb.html
      id="lkvNNrmhhNk"
      title="Nivea" %}
  </div>
</div>

---

for more commercials project please check out here
[YouTube Playlist](https://youtube.com/playlist?list=PLsNok4h-_iVww3xZIRipgJGfunXY5n2mw&si=W_o7qfA2iFf4qLOV){: .btn .btn--primary .btn--small} 
