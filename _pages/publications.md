---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Self-regulated Learning](#SRL)
[Multimodal Learning Analytics](#multimodal-learning-analytics)\
[Mixed Methods](#mixed-methods)\

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Self-regulated Learning
{% for post in site.publications reversed %}
  {% if type == 'SRL' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Tables

| Author          | Year   |  Title                                                       |  Venue      |   Hyperlink  |
| ----------------| -------| ------------------------------------------------------------ | ------------|  ------------|  
| [Paper 1](#)    | 2016   | Description of the item in the list                          |             |              |
| [Paper 2](#)    | 2019   | Description of the item in the list                          |             |              |
| [Paper 3](#)    | 2022   | Description of the item in the list                          |             |              |

## Multimodal Learning Analytics
{% for post in site.publications reversed %}
  {% if type == 'MLA' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Tables

| Author          | Year   |  Title                                                       |  Venue      |   Hyperlink  |
| ----------------| -------| ------------------------------------------------------------ | ------------|  ------------|  
| [Paper 1](#)    | 2016   | Description of the item in the list                          |             |              |
| [Paper 2](#)    | 2019   | Description of the item in the list                          |             |              |
| [Paper 3](#)    | 2022   | Description of the item in the list                          |             |              |

## Mixed Methods
{% for post in site.publications reversed %}
  {% if type == 'mixed-methods' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Tables

| Author          | Year   |  Title                                                       |  Venue      |   Hyperlink  |
| ----------------| -------| ------------------------------------------------------------ | ------------|  ------------|  
| [Paper 1](#)    | 2016   | Description of the item in the list                          |             |              |
| [Paper 2](#)    | 2019   | Description of the item in the list                          |             |              |
| [Paper 3](#)    | 2022   | Description of the item in the list                          |             |              |
