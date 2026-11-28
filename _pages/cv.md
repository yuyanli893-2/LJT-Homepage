---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

* Ph.D. in Computer Science, Hong Kong University of Science and Technology (HKUST), 2024–Present
* B.Eng., Shanghai Jiao Tong University (SJTU), 2020–2024

# Research Experience

* February 2025 – Present: Research Intern, MINIMAX
* June 2024 – September 2024: Research Intern, Tencent WXG
* June 2023 – December 2023: Research Intern, Shanghai AI Lab

# Skills

* Natural Language Processing (NLP)
* Machine Learning (ML)
* Large Language Models (LLMs)
* Reinforcement Learning
* Vision-Language Models (VLM)
* Hallucination Detection and Mitigation
* LLM Truthfulness and Interpretability

# Awards

* Zhiyuan Honor Scholarship — Shanghai Jiao Tong University

# Publications

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Talks

<ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

# Teaching

<ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}  
  {% endfor %}</ul>
