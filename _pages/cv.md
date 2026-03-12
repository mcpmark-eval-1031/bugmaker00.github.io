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
* **Ph.D. in Computer Science** (2024 - Present)  
  Hong Kong University of Science and Technology (HKUST)  
  Advisor: Prof. Junxian He

* **B.Eng.** (2020 - 2024)  
  Shanghai Jiao Tong University (SJTU)  
  Zhiyuan College

Research Experience
======
* **Research Intern**, MINIMAX (February 2025 - Present)
  * Research on large language models and reasoning capabilities.

* **Research Intern**, Tencent WXG (June 2024 - September 2024)
  * Research on vision-language models for chart understanding.
  * Mentor: Zifei Shan

* **Research Intern**, Shanghai AI Lab (June 2023 - December 2023)
  * Research on truthfulness and interpretability of large language models.
  * Mentor: Prof. Yu Cheng

Awards and Honors
======
* **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University

Skills
======
* **Natural Language Processing**: Large Language Models, Vision-Language Models, Logical Reasoning, Hallucination Mitigation, Interpretability
* **Machine Learning**: Reinforcement Learning, Representation Learning, Parameter-Efficient Fine-Tuning
* **Programming**: Python, PyTorch, Git, LaTeX
* **Languages**: Chinese (Native), English (Fluent)

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

Service
======
* Reviewer for top-tier NLP and ML venues
