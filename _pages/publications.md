---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(*) denotes equal contribution
---
* [Statistical Perspective of Top-K Sparse Softmax Gating Mixture of Experts](https://arxiv.org/pdf/2309.13850.pdf)
Proceedings of the ICLR, 2024.
Huy Nguyen, Pedram Akbarian, Fanqi Yan, Nhat Ho
---
* [Is Parameter Learning via Weighted Model Integration Tractable?](https://openreview.net/pdf?id=eecWixvAEeZ)
TPM Workshop at UAI 2021
Zhe Zeng*, Paolo Morettin*, Fanqi Yan*, Antonio Vergari, Guy Van den Broeck
---
Probabilistic Inference with Algebraic Constraints: Theoretical Limits and Practical Approximations
NeurIPS 2020     Spotlight presentation, acceptance rate 280/9454 = 2.96%
Zhe Zeng*, Paolo Morettin*, Fanqi Yan*, Antonio Vergari, Guy Van den Broeck
---
Relax, Compensate and then Integrate
DeCoDeML Workshop at ECML-PKDD 2020
Zhe Zeng*, Paolo Morettin*, Fanqi Yan*, Antonio Vergari, Guy Van den Broeck
---
Scaling up Hybrid Probabilistic Inference with Logical and Arithmetic Constraints via Message Passing
ICML 2020
Zhe Zeng*, Paolo Morettin*, Fanqi Yan*, Antonio Vergari, Guy Van den Broeck
---
Hybrid Probabilistic Inference with Logical Constraints: Tractability and Message Passing
KR2ML Workshop at NeurIPS 2019
Zhe Zeng*, Fanqi Yan*, Paolo Morettin*, Antonio Vergari, Guy Van den Broeck
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
