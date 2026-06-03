---
permalink: /about/
title: about <i class="fa-solid fa-address-card"></i>
author_profile: true
---

![ip-modular_lo-s]({{ site.url }}{{ site.baseurl }}/assets/images/ip/ip-modular_lo-s.jpg){: .align-center}

**INDRA PERKASA**
{: .text-right}
started his music studies at [Institut Musik Daya Indonesia (IMDI)](https://dayaindonesiapaacademy.id/) in 2001 and graduated in 2006 majoring in double bass and composition.<br> Having found his roots in jazz music, he has been the bass player of [Tomorrow People Ensemble](https://open.spotify.com/artist/665hyF3eRIADYsNEr8Xdqi?si=V2hLDi8WSaujLtP29XnU0Q) since its founding in 2005.
{: .text-right}

![ip-circlelight2]({{ site.url }}{{ site.baseurl }}/assets/images/ip/ip-mic-bench2.jpg)

A year after he graduated from IMDI, he continued his study concentrating in film scoring at [UCLA Extension (Los Angeles)](https://www.uclaextension.edu/entertainment/music/certificate/film-scoring), where he got to learn from various notable film composers such as [Thom Sharp](https://www.uclaextension.edu/instructors/thom-sharp), [Robert Drasnin](https://en.wikipedia.org/wiki/Robert_Drasnin), [Richard Marvin](https://en.wikipedia.org/wiki/Richard_Marvin_(composer)), [Craig Stuart Garfinkle](https://www.craigstuartgarfinkle.com/).
{: .text-right}

As a seasoned film composer and producer, Indra creates
scores that are integral to the cinematic narrative, seamlessly blends emotional depth and diverse musical genres with stylistic innovation to create unique and memorable soundscapes for film and other media.
{: .text-right}

![ip-modular-pose1]({{ site.url }}{{ site.baseurl }}/assets/images/ip/ip-modular-pose1.jpg)

---

### displaying an index of posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---
### using tags
All tags registered in the current site are exposed to Liquid templates via `site.tags`. Iterating over `site.tags` on a page will yield another array with two items, where the first item is the name of the tag and the second item being an *array of posts* with that tag.
{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}  
