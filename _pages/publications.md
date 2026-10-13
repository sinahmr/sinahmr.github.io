---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /presentations/
  - /talks/
description: "Publications by Sina Hajimiri on LLM agents, agent evaluation, vision transformers, and vision-language models (EMNLP, ICLR, CVPR, WACV, MICCAI)."
---

{% include base_path %}

<p class="page__lead-note">Also on <a href="{{ site.author.googlescholar }}">Google Scholar</a>. <u>Underlined</u>: me.</p>

{% for p in site.data.publications %}
{% include pub.html pub=p %}
{% endfor %}
