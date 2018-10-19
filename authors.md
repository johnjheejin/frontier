---
layout: page
title: 글쓰는 사람들
permalink: /authors/
sitemap:
  priority: 0.7
---
{% for author in site.authors %}
* [{{ author.name }}]({{ site.baseurl }}/authors/{{ author.name }}) : {{ author.bio }}
{% endfor %}
