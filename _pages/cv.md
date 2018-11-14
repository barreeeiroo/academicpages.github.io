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
  * International Baccalaureate, _expected_ May 2019
  * Título de Bachiller Español, _expected_ June 2019
  * Avaluación do Bacharalato para o Acceso á Universidad, _expected_ June 2019

Work experience
======
* [Makeroid / Kodular](https://www.kodular.io)
  * CoFounder & Programmer
  * July 2017 - Now
  
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
{% assign sorted2 = (site.press | sort: 'date') | reverse %}
  <ul>{% for post in sorted2 limit: 5 %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
