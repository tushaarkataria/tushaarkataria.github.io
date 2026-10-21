---
layout: archive
title: "Publications"
permalink: /publication_list/
author_profile: true
redirect_from:
  - /publications/
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a></u>.
{% endif %}

{% include base_path %}

{% assign pubs = site.publications | sort: "date" | reverse %}
<ol>
{% for pub in pubs %}
  {% assign cite = pub.citation | replace: "Tushar Kataria", "<b>Tushar Kataria</b>" | replace: "Kataria, Tushar", "<b>Kataria, Tushar</b>" | replace: "Kataria, T.", "<b>Kataria, T.</b>" | replace: "T. Kataria", "<b>T. Kataria</b>" %}
  <li style="margin-bottom: 1em;">
    {{ cite }}
    <br>
    <i>{{ pub.venue }}</i>, {{ pub.date | date: "%Y" }}.
    {% if pub.paperurl %}[<a href="{{ pub.paperurl }}">Paper</a>]{% endif %}
    {% if pub.archive %}[<a href="{{ pub.archive }}">arXiv</a>]{% endif %}
    [<a href="{{ base_path }}{{ pub.url }}">Abstract</a>]
  </li>
{% endfor %}
</ol>
