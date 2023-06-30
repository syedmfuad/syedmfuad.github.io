---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

As an applied microeconomist, my work involves developing programmable stochastic models that employ very high-resolution data. In particular, I study the behavior of persons in social networks; uncover latent socioeconomic disparities in housing markets; and fuse econometric tools with optimization modeling to better use biomass waste to biopower production.

The emphasis on high-resolution data coupled with complex, emerging methodologies to manage very local and specific resources in a very targeted way is a common theme of my research. Broadly, my two most competitive skills are the ability to locate very quickly, very high-resolution data that then demand advanced numerical methods to answer these highly nuanced policy questions that also enjoy immediate currency in public discourse. Requests for drafts of working papers are welcome. Please feel free to email me your request.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
