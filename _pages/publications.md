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
# Publications
## Conference

**Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding**
- Xintong Wang, **Jingheng Pan**, Liang Ding, and Chris Biemann,
- Findings of the Association for Computational Linguistics (ACL). August 2024 **(Core Rank A\*)**
- [arxiv](https://arxiv.org/abs/2403.18715), [Github](https://github.com/p1k0pan/ICD)
