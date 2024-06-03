---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[[paper](https://arxiv.org/abs/2404.08181), [code](https://github.com/sinahmr/NACLIP)] <u>Hajimiri, S.</u>, Ben Ayed, I. and Dolz, J. **Pay Attention to Your Neighbours: Training-Free Open-Vocabulary Semantic Segmentation**. *arXiv preprint arXiv:2404.08181*, 2024.

[[paper](https://arxiv.org/abs/2312.12730), [code](https://github.com/jusiro/CLAP)] Silva-Rodriguez, J., <u>Hajimiri, S.</u>, Ben Ayed, I., and Dolz, J. **A Closer Look at the Few-Shot Adaptation of Large Vision-Language Models**. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 2024.

[[paper](https://arxiv.org/abs/2211.14126), [code](https://github.com/sinahmr/DIaM)] <u>Hajimiri, S.</u>, Boudiaf, M., Ben Ayed, I., and Dolz, J. **A Strong Baseline for Generalized Few-Shot Semantic Segmentation**. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition* (pp. 11269-11278), 2023.

[[paper](https://arxiv.org/abs/2102.00892), [code](https://github.com/sinahmr/parted-vae)] <u>Hajimiri, S.</u>, Lotfi, A., and Soleymani Baghshah, M. **Semi-Supervised Disentanglement of Class-Related and Class-Independent Factors in VAE**. *arXiv preprint arXiv:2102.00892*, 2021.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
