---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Statistical Perspective of Top-K Sparse Softmax Gating Mixture of Experts. 
Proceedings of the ICLR, 2024.
Huy Nguyen, Pedram Akbarian, Fanqi Yan, Nhat Ho


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
