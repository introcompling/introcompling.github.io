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

# Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

# Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Getting Started

Getting started with Just the Class is simple.

1. Create a [new repository based on Just the Class](https://github.com/kevinlin1/just-the-class/generate).
1. Update `_config.yml` and `README.md` with your course information. [Be sure to update the url and baseurl](https://mademistakes.com/mastering-jekyll/site-url-baseurl/).
1. Configure a [publishing source for GitHub Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages). Your course website is now live!
1. Edit and create `.md` [Markdown files](https://guides.github.com/features/mastering-markdown/) to add more content pages.

Just the Class has been used by instructors at Stanford University ([CS 161](https://stanford-cs161.github.io/winter2021/)), UC Berkeley ([Data 100](https://ds100.org/fa21/)), UC Santa Barbara ([CSW8](https://ucsb-csw8.github.io/s22/)), Northeastern University ([CS4530/5500](https://neu-se.github.io/CS4530-CS5500-Spring-2021/)), and Carnegie Mellon University ([17-450/17-950](https://cmu-crafting-software.github.io/)). Share your course website and find more examples in the [show and tell discussion](https://github.com/kevinlin1/just-the-class/discussions/categories/show-and-tell)!

### Local development environment

Just the Class requires no special Jekyll plugins and can run on GitHub Pages' standard Jekyll compiler. To setup a local development environment, clone your template repository and follow the GitHub Docs on [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll).
