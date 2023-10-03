---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2023

[[paper](https://arxiv.org/abs/2211.14126), [code](https://github.com/sinahmr/DIaM)] <u>Hajimiri, S.</u>, Boudiaf, M., Ben Ayed, I., & Dolz, J. (2023). **A Strong Baseline for Generalized Few-Shot Semantic Segmentation**. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (pp. 11269-11278).

___

## 2021

[[paper](https://arxiv.org/abs/2102.00892), [code](https://github.com/sinahmr/parted-vae)] <u>Hajimiri, S.</u>, Lotfi, A., & Soleymani Baghshah, M. (2021). **Semi-Supervised Disentanglement of Class-Related and Class-Independent Factors in VAE**. *arXiv preprint arXiv:2102.00892*.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
