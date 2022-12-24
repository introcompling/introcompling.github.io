---
layout: home
title: Intro to Computation for Linguists, Spring 2023
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: CompLing DeCal
---

# Welcome!
This is the first-ever iteration of a DeCal designed to provide aspiring linguists with an easily accessible introduction to computing. The course is primarily lab-based and will also end with a group project. 
We highly recommend students to have taken Linguistics 100 or equivalent. The course is also designed for students with no programming experience.
## Staff
Our faculty advisor is [Prof. Terry Regier](mailto:terry.regier@berkeley.edu).
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
## Calendar
{% for module in site.modules %}
{{ module }}
{% endfor %}
