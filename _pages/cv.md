---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV as PDF](/files/Rui_Li_CV.pdf){: .btn .btn--primary}

Education
======
* Ph.D. in Computer Science, Leiden Institute of Advanced Computer Science (LIACS), Leiden University, 2021–2026 (expected)
  * Research focus: Explainable AI in Malware Detection
  * Supervisor: Olga Gadyatskaya
* M.Sc. in Electronic Engineering, Beijing Institute of Technology, 2017–2020
  * Thesis: Explainable Android Malware Detection Methods
* B.Sc. in Electronic Engineering & Economics (Dual Degree), Beijing Institute of Technology, 2013–2017

Research experience
======
* **Large Language Models (LLMs)**
  * Designed LLM-based semantic alignment pipelines for structured knowledge reasoning on large real-world datasets.
  * Developed and compared prompting strategies (zero-shot, few-shot) to improve semantic matching.
  * Benchmarked commercial API-based and open-source LLMs using ranking-based metrics (Accuracy, NDCG).
* **Explainable AI and Model Interpretability**
  * Developed and evaluated interpretability methods for classification and clustering models.
  * Designed quantitative metrics (stability, robustness, effectiveness) for explanation quality.
  * Conducted empirical studies comparing human-annotated and model-generated explanations.

Work experience
======
* Jul 2020 – Jul 2021: Security Software Test Engineer, China National FinTech Evaluation Center, Beijing
  * Security evaluation of Electronic Social Insurance Card software (Fortify, SonarQube, Burp Suite).
  * Security testing on Samsung and Golden River V-Trust Trusted Execution Environment (TEE).
* Apr 2019 – Sep 2019: Machine Learning Engineer (Intern), Tsinghua University, Beijing
  * Built a multi-factor quantitative investment strategy system using a random herd optimization algorithm.

Skills
======
* Programming: Python, R
* Libraries/Tools: PyTorch/TensorFlow, HuggingFace, Scikit-learn, Git, Linux
* Languages: English (full professional), Chinese (mother tongue), Dutch (A2)

Publications
======
<ul>{% assign cv_pubs = site.publications | sort: 'date' | reverse %}{% for post in cv_pubs %}
  <li>{{ post.citation }}</li>
{% endfor %}</ul>

Talks
======
<ul>{% assign cv_talks = site.talks | sort: 'date' | reverse %}{% for post in cv_talks %}
  <li><strong>{{ post.venue }}</strong>, {{ post.location }}, {{ post.date | default: "1900-01-01" | date: "%Y" }} — <i>{{ post.title }}</i></li>
{% endfor %}</ul>

Teaching & supervision
======
<ul>{% assign cv_teach = site.teaching | sort: 'date' | reverse %}{% for post in cv_teach %}
  <li>{{ post.years }} — <strong>{{ post.title }}</strong> ({{ post.type }}): {{ post.thesis }}</li>
{% endfor %}</ul>

Awards
======
* China Scholarship Council, May 2021
* Winning Prize, Global (Nanjing) AI Application Competition, 2018
* Outstanding Graduates, Beijing Institute of Technology, 2017
* Silver Award, iGEM (International Genetically Engineered Machine), 2016
* Meritorious Winner, Mathematical Contest in Modeling, 2016
* University Scholarship (7 times), 2013–2020

Service
======
* Program Committee Member, 3rd International Conference on Data Science & AI (DSAI), 2025
* Event organization, Ethics in Cybersecurity and AI, Leiden University, 2025
* Event organization, LIACS PhD Weekend, Leiden University, 2025
