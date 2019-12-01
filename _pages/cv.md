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
* IES Rosalía de Castro (2013-2019)
  * International Baccalareate
  * Título de Bachiller Español
* Universidad de Santiago de Compostela (2019-2024)
  * Bachelor of Science in Computer Science (_expected_)

Work experience
======
* [Kodular](https://www.kodular.io)
  * Co-Founder & Chief Technical Officer (_Makeroid_) 
    * July 2017 - July 2019
  * Chief Executive Officer (_Junnovate, LLC_)
    * July 2019 - Now
  
Skills
======
* Management of Servers Infrastructure
  * App Engine and related at Google Cloud Platform
  * Elastic Beanstalk and related at Amazon Web Services
* Programming
  * Python, including _Django_
  * Java, worked with _ant_ and _Android_
  * PHP, focused for web development
  * C
  * Lua

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
