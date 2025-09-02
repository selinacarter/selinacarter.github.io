---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-DFNFSM90G3"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-DFNFSM90G3');
</script>


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



## Current projects

* Thesis proposal (September 2, 2025): 
<a href="http://selinacarter.github.io/files/Proposal_Selina_Carter.pdf" download>"Uncertainty quantification and inference using online methods and neural networks"</a>
* Inference using online algorithms: My early focus with my advisor, Arun Kuchibhotla, has centered on inference under minimal assumptions in online settings. This work is ongoing and is summarized in ["Statistical Inference for Online Algorithms"](https://arxiv.org/html/2505.17300v1).
* Neural network ensembles for UQ --- Project 2 of dissertation 
* Prediction intervals for streaming time series using prior finite-horizon data --- Project 3 of dissertation



## Submitted papers and pre-prints

* (Coming soon) Carter, S., Chen, J. and Schneider, J. "Variance-free Inference of Neural Network Ensembles
 for Uncertainty Quantification." NeurIPS 2025 submission.
* (Pre-print) Carter, S. and Kuchibhotla, A. ["Statistical Inference for Online Algorithms."](https://arxiv.org/html/2505.17300v1) arXiv preprint arXiv:2505.17300v1 (2025).
* (Pre-print) Meyer, M. J., Carter, S., Mordukhovich, I., McNeely, E., Malloy, E. J. ["Model Selection in Variational Mixed Effects Models.”](https://arxiv.org/abs/2206.04012) arXiv preprint arXiv:2206.04012 (2022).
* (Pre-print) Hersh J., Carter S. [“Explainable AI Helps Bridge the AI Skills Gap: Evidence from a Large Bank.”](https://digitalcommons.chapman.edu/economics_articles/276/) Chapman University Digital Commons.
* "Modeling COVID-19 testing rates by occupation among U.S. adults." Advanced Data Analysis Project (required for second-year PhD students in statistics at CMU), advised by Alex Reinhart and Robin Mejia.


## Conferences

<img src="/images/INFORMS_APS_HulC_poster_Selina.jpg" alt="Poster at INFORMS-APS 2025" width="50%">

* "Statistical Inference for Online Algorithms" (presented by S. Carter; joint with A. Kuchibhotla)
  * (Forthcoming) Joint Statistical Meetings (JSM) 2025 - Nashville, TN (08/02/2025) - contributed talk + roundtable
  * INFORMS-APS 2025 - Georgia Tech (07/02/2025) - contributed talk, poster, and lightning talk
  * Kansas Women in Math Symposium 2025 - Wichita State (04/27/2025) - poster and lightning talk
  * Symposium on Data Science and Statistics (SDSS) 2025 - Salt Lake City, UT (04/27/2025) - poster
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




