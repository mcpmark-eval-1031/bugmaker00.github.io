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
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024-Present (expected)
* **B.Eng.**, Shanghai Jiao Tong University, 2020-2024 (Graduated with Zhiyuan Honor Scholarship)

Work experience
======
* **Research Intern**, MINIMAX (February 2025 - Present)
  * Conducting research on large language models and reasoning.
  * Supervisor: N/A

* **Research Intern**, Tencent WXG (June 2024 - September 2024)
  * Worked on vision-language models for chart understanding.
  * Supervisor: Zifei Shan

* **Research Intern**, Shanghai AI Lab (June 2023 - December 2023)
  * Research on truthfulness and interpretability of LLMs.
  * Supervisor: Prof. Yu Cheng

Skills
======
* **Natural Language Processing**: Large Language Models, Vision-Language Models, Logical Reasoning, Hallucination Mitigation
* **Machine Learning**: Reinforcement Learning, Representation Learning, Model Evaluation
* **Programming**: Python, PyTorch, JAX, Git, LaTeX
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

Service and leadership
======
* Reviewer for top-tier conferences (e.g., EMNLP, ICML, NeurIPS)
* Volunteer for academic community events