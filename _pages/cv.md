---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<object data="http://tushaarkataria.github.io/files/cv.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="http://tushaarkataria.github.io/files/cv.pdf">
        
    </embed>
</object>

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
  
