---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  (*) denotes equal contribution, (+) denotes co-last authors
+ [Sigmoid Self-Attention is Better than Softmax Self-Attention: A Mixture-of-Experts Perspective](https://arxiv.org/abs/2410.12258) <br /> ArXiv <br />Fanqi Yan\*, Huy Nguyen\*, Pedram Akbarian, Nhat Ho $\dagger$, Alessandro Rinaldo\+

+ [Understanding Expert Structures on Minimax Parameter Estimation in Contaminated Mixture of Experts](https://arxiv.org/abs/2410.12258) <br /> AISTATS 2025 <br />Fanqi Yan\*, Huy Nguyen\*, Dung Le\*, Pedram Akbarian, Nhat Ho

+ [Statistical Perspective of Top-K Sparse Softmax Gating Mixture of Experts](https://arxiv.org/pdf/2309.13850.pdf) <br /> ICLR 2024 <br />Huy Nguyen, Pedram Akbarian, Fanqi Yan, Nhat Ho


+ [Is Parameter Learning via Weighted Model Integration Tractable?](https://openreview.net/pdf?id=eecWixvAEeZ)
  <br />TPM Workshop at UAI 2021
  <br />Zhe Zeng\*, Paolo Morettin\*, Fanqi Yan\*, Antonio Vergari, Guy Van den Broeck


+ [Probabilistic Inference with Algebraic Constraints: Theoretical Limits and Practical Approximations](https://proceedings.neurips.cc/paper/2020/hash/85934679f30131d812a8c7475a7d0f74-Abstract.html)
  <br />NeurIPS 2020, Spotlight presentation, acceptance rate 280/9454 = 2.96%
  <br />Zhe Zeng\*, Paolo Morettin\*, Fanqi Yan\*, Antonio Vergari, Guy Van den Broeck


+ [Relax, Compensate and then Integrate](https://web.cs.ucla.edu/~zhezeng/publication/ecml20/ecml20.pdf)
  <br />DeCoDeML Workshop at ECML-PKDD 2020
  <br />Zhe Zeng\*, Paolo Morettin\*, Fanqi Yan\*, Antonio Vergari, Guy Van den Broeck


+ [Scaling up Hybrid Probabilistic Inference with Logical and Arithmetic Constraints via Message Passing](https://proceedings.mlr.press/v119/zeng20a/zeng20a.pdf)
  <br />ICML 2020
  <br />Zhe Zeng\*, Paolo Morettin\*, Fanqi Yan\*, Antonio Vergari, Guy Van den Broeck

  
+ [Hybrid Probabilistic Inference with Logical Constraints: Tractability and Message Passing](https://arxiv.org/pdf/1909.09362.pdf)
  <br />KR2ML Workshop at NeurIPS 2019
  <br />Zhe Zeng\*, Fanqi Yan\*, Paolo Morettin\*, Antonio Vergari, Guy Van den Broeck

   

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Conference Reviewing:
ICML 2024, ICLR 2025
