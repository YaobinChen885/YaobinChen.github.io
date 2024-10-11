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
* Ph.D in Mathematics, [Fudan univerisity](https://www.fudan.edu.cn/en/) 2026 (expected), supervisor: [Hehui Wu](https://scms.fudan.edu.cn/info/2672/4987.htm).
* B.S. in Mathematics, [University of Science and Technology of China](https://en.ustc.edu.cn/), 2021
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
