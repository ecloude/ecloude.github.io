---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Multimodal Learning Analytics](#multimodal-learning-analytics)\
[Mixed Methods](#mixed-methods)\
[Self-regulated Learning](#SRL)

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Multimodal Learning Analytics
{% for post in site.publications reversed %}
  {% if post.pubtype == 'MLA' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Mixed Methods
{% for post in site.publications reversed %}
  {% if post.pubtype == 'mixed-methods' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Self-regulated Learning
{% for post in site.publications reversed %}
  {% if post.pubtype == 'SRL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
