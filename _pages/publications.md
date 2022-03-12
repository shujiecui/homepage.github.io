---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

1. [AsiaCCS 2022] **EnclaveTree: Privacy-preserving Data Stream Training and Inference Using TEE** 
   Qifan Wang, Shujie Cui, Lei Zhou, Ocean Wu, Yonghua Zhu, Giovanni Russello 
   The 17th ACM ASIA Conference on Computer and Communications Security 
   [pdf](http://shujiecui.github.io/files/enclavetree.pdf) Acceptance rate 18.5%


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
