---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



## Current projects


* My early focus with Professor Kuchibhotla has centered on inference under minimal assumptions in online settings. To demonstrate the utility of inference via his work, ["Confidence Regions from Convex Hulls" (HulC)](https://arxiv.org/abs/2105.14577), I ran simulations to compare HulC-based confidence intervals using stochastic gradient descent against traditional methods. We are drafting a paper on these results. As a member of CMU's [Statistical Machine Learning Reading Group](http://statml.cs.cmu.edu/), I presented our early results in February 2024 as well as proof sketches from [Chen et al's "Statistical Inference for Model Parameters in Stochastic Gradient Descent"](https://arxiv.org/abs/1610.08637).

* Disaster management using uncertainty quantification in reinforcement learning (AI Institute for Societal Decision Making at CMU), topic of 2024 summer research



Submitted papers and pre-prints
======

* (Pre-print) Meyer, M. J., Carter, S., Mordukhovich, I., McNeely, E., Malloy, E. J. ["Model Selection in Variational Mixed Effects Models.”](https://arxiv.org/abs/2206.04012) arXiv preprint arXiv:2206.04012 (2022).
* (Pre-print) Hersh J., Carter S. [“Explainable AI Helps Bridge the AI Skills Gap: Evidence from a Large Bank.”](https://digitalcommons.chapman.edu/economics_articles/276/) Chapman University Digital Commons.
* "Modeling COVID-19 testing rates by occupation among U.S. adults." Advanced Data Analysis Project (required for second-year PhD students in statistics at CMU), advised by Alex Reinhart and Robin Mejia.


Conferences
======

* "Will AI Accelerate the Intra-Firm Digital Divide? Evidence from a Field Experiment on How Managers use Explainable AI" (Presented by co-author Jonathan Hersh)
  * MIT Conference on Digital Experimentation (CODE) (11/10/2023)
  * Wharton/Columbia Management, Analytics and Data (MAD) (5/19/2023)
  * USC Artificial Intelligence in Management, AIM 2023 (3/16/2023) – Best PhD Student Paper Award
  * Statistical Challenges in E-Commerce Research (6/2022)
  * Global Conference on Innovations in Management and Business (2021)
  * INFORMS Conference on Information Systems & Technology (CIST) (2020)
* Predicting Delays at the Inter-American Development Bank Using R. R-Gov Conference (Lander Analytics and Georgetown University). [recording](https://www.youtube.com/watch?v=fWfSGI-pf0A) (12/2020)
* How Are Ideas Spread at Your Organization? Analyze Its Citation Network. R-Gov Conference (Lander Analytics and Georgetown University). [recording](https://www.youtube.com/watch?v=Y_ZGjE5rUwU) (11/2019)
* The IDB Loan Network: Assessing the Role of Impact Evaluations. Sunbelt 2019 (International Network for Social Network Analysis, Montreal). (6/2019) [Check out the cool viz I made.](https://www.youtube.com/watch?v=7Wxqc2A8ZMw)
