---
layout: default
title: Home
---
# Ruichen Xu

![avatar](/assets/img/avatar.jpg){: .avatar}

**Ruichen Xu**  
PhD Student in Applied Mathematics  
[Stony Brook University](https://www.stonybrook.edu)

[Google Scholar]({{ site.social.scholar }}) / [GitHub]({{ site.social.github }}) / [LinkedIn]({{ site.social.linkedin }})

## Introduction
I am a PhD student specializing in AI for Science, with research in neural operators, machine learning-based PDE solvers, and stochastic optimization. My work aims to bridge theory and application in data-limited and physics-informed scenarios.

Research focus areas:
- **AI4PDE** — Neural operators for PDE families, active learning strategies.
- **Stochastic Optimization** — Reinforcement learning-guided simulated annealing.
- **AI4Drug** — Computational drug design and molecular optimization.

> **Prospective Students**: Please check the [Prospective Students](/prospective/) and [Topics](/topics/) pages.

## News
<ul class="news">
{% assign items = site.news | sort: 'date' | reverse | slice: 0, 10 %}
{% for item in items %}
  <li>
    <span class="date">[{{ item.date | date: "%Y.%m" }}]</span>
    <span class="entry">{{ item.title | markdownify | remove: '<p>' | remove: '</p>' }}</span>
  </li>
{% endfor %}
</ul>
