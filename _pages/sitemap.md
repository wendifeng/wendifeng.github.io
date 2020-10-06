---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

Home Page
---
[Home Page]({{ base_path }})


A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

Selected Publications
---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Résumé
---

[[Résumé]](http://wendifeng.github.io/files/CV_wendi.pdf)<br/>
[[中文简历]](http://wendifeng.github.io/files/CV_Chinese_wendi.pdf)