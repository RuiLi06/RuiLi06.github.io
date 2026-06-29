---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Currently, I am a PhD candidate in Computer Science at Leiden University, supervised by Olga Gadyatskaya, working on Explainable AI (XAI), trustworthy machine learning, Large Language Models (LLMs), and AI-driven security. My research investigates how AI-based security systems can be made more transparent, reliable, and actionable for human analysts.

Research interests
======
- **Explainable AI (XAI)**
- **LLMs for security**
- **Malware detection & analysis**

Education
======
- **PhD in Computer Science**, Leiden Institute of Advanced Computer Science (LIACS), Leiden University, 2021–2026 (expected) — Explainable AI in Malware Detection.
- **MSc in Electronic Engineering**, Beijing Institute of Technology, 2017–2020 — Thesis: Explainable Android Malware Detection Methods.
- **BSc in Electronic Engineering & Economics** (Dual Degree), Beijing Institute of Technology, 2013–2017.

Publications
======
<ul>{% assign home_pubs = site.publications | sort: 'date' | reverse %}{% for post in home_pubs %}
  <li>{{ post.citation }}</li>
{% endfor %}</ul>

Awards
======
- China Scholarship Council, May 2021
- Winning Prize, Global (Nanjing) AI Application Competition, 2018
- Outstanding Graduates, Beijing Institute of Technology, 2017
- Silver Award, iGEM (International Genetically Engineered Machine), 2016
- Meritorious Winner, Mathematical Contest in Modeling, 2016
- University Scholarship (7 times), 2013–2020

See my [talks](/talks/) and [teaching](/teaching/) for more.
