---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Self-regulated Learning Processes](#SRL)
The heart of my research is situated in learning analytics, learning sciences, instructional design, and educational technology. My ultimate research goal is to develop intelligent and adaptive learning technologies that could enhance the accessibility, inclusivity, and overall quality of digital education, making the benefits of SRL accessible to all types of learners.

To achieve this goal, it requires studying SRL comprehensively, as a process with four underlying components: cognition, affect, metacognition, and motivation (CAMM) which serve as the bedrock for effective self-regulation during learning (SRL). Studying SRL as a process that unfolds over time requires collecting fine-grained and continuous data streams of underlying CAMM processes that transpire during learning activities with educational software.

As such, my publications are organized by two process-oriented approaches with diverse learning technologies. One that utilizes multimodal data streams (solely relying on quantitative measures) and the other that harnesses the power of mixed-multimodal methods (merging quantitaive and qualitative measures).

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Multimodal Learning Analytics
{% for post in site.publications reversed %}
  {% if type == 'MLA' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Table 1

| Author          | Year   |  Title                                      |  Venue      | Hyperlink  | Learning Software |
| ----------------| -------| ------------------------------------------- | ------------|------------|-------------------| 
| [2020-07-03](#)    | 2020   | Description of the item in the list         |             |            |Game-based Learning|
| [Paper 2](#)    | 2019   | Description of the item in the list         |             |            |                   |
| [Paper 3](#)    | 2022   | Description of the item in the list         |             |            |                   |


## Mixed-Multimodal Methods
{% for post in site.publications reversed %}
  {% if type == 'mixed-methods' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Table 2

| Author          | Year   |  Title                                                       |  Venue      |   Hyperlink  |
| ----------------| -------| ------------------------------------------------------------ | ------------|  ------------|  
| [Paper 1](#)    | 2016   | Description of the item in the list                          |             |              |
| [Paper 2](#)    | 2019   | Description of the item in the list                          |             |              |
| [Paper 3](#)    | 2022   | Description of the item in the list                          |             |              |
