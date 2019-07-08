---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* IES Rosalía de Castro
  * International Baccalaureate
  * Título de Bachiller Español

Work experience
======
* [Kodular](https://www.kodular.io)
  * Co-Founder & Chief Technical Officer (_Makeroid_) 
    * July 2017 - July 2019
  * Chief Executive Officer (_Junnovate, LLC_)
    * July 2019 - Now
  
Skills
======
* Management of Linux Servers
* Programming
  * PHP + Web Languages
  * Java + Android
  * Lua
  * Python

Hobbies
======
* Volunteer at Civil Defense of Santiago de Compostela
* Tennis Player
* Cycling

In Press
======
{% assign sorted1 = (site.press | sort: 'date') | reverse %}
  <ul>{% for post in sorted1 limit: 5 %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
{% assign sorted2 = (site.talks | sort: 'date') | reverse %}
  <ul>{% for post in sorted2 limit: 5 %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
