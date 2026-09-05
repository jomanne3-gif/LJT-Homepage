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
* Ph.D. in Computer Science (2024–Present), Hong Kong University of Science and Technology (HKUST)
* B.Eng. (2020–2024), Shanghai Jiao Tong University (SJTU)

Work experience
======
* 2025–Present: Research Intern
  * MINIMAX
* 2024 (June–September): Research Intern
  * Tencent WXG
* 2023 (June–December): Research Intern
  * Shanghai AI Lab

Skills
======
* Natural language processing
* Machine learning
* LLM reasoning and reinforcement learning
* Hallucination in vision-language models
* LLM truthfulness and interpretability

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
