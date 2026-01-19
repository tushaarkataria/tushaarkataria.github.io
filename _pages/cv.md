---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Updated CV Academic](http://tushaarkataria.github.io/files/cv.pdf)
[Updated CV Professional](http://tushaarkataria.github.io/files/CV_Corporate.pdf)

<span style="color:blue;">Publications</span>
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<span style="color:orange;">Talks</span>
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<span style="color:purple;">Teaching</span>
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
