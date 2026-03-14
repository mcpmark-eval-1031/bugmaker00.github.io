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
* **Ph.D. in Computer Science** (2024 – Present)  
  Hong Kong University of Science and Technology (HKUST), Hong Kong, China  
  Advisor: Prof. Junxian He

* **B.Eng.** (2020 – 2024)  
  Shanghai Jiao Tong University (SJTU), Shanghai, China  
  Zhiyuan College

Research Experience
======
* **Research Intern**, MINIMAX (February 2025 – Present)
  * Research on large language model reasoning and reinforcement learning.

* **Research Intern**, Tencent WXG (June 2024 – September 2024)
  * Research on vision-language models for chart understanding and hallucination mitigation.
  * Mentor: Zifei Shan

* **Research Intern**, Shanghai AI Lab (June 2023 – December 2023)
  * Research on LLM truthfulness, interpretability, and internal representations.
  * Mentor: Prof. Yu Cheng

Awards and Honors
======
* **Zhiyuan Honor Scholarship**, Shanghai Jiao Tong University (2020 – 2024)

Skills
======
* **Natural Language Processing**: Large Language Models (LLMs), Vision-Language Models (VLMs), Logical Reasoning, Hallucination Mitigation, LLM Interpretability & Truthfulness
* **Machine Learning**: Reinforcement Learning from Human Feedback (RLHF), Reinforcement Learning, Representation Learning, Parameter-Efficient Fine-Tuning
* **Programming**: Python, PyTorch, Git, LaTeX, Bash
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
* Reviewer for top-tier NLP and ML venues (ACL, EMNLP, NAACL, NeurIPS, ICML)
