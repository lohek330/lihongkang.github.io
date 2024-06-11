---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">My publications can be found at <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

# Preprints

# Conference Papers
1. **Hongkang Li***, Meng Wang, Sijia Liu, Pin-Yu Chen, Jinjun Xiong. [Generalization Guarantee of Training Graph Convolutional Networks with
Graph Topology Sampling](https://arxiv.org/pdf/2207.03584), ICML 2022. 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
