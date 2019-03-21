---
layout: default
img: docs.jpg
category: Documentation
id: documentation
title: Documentation
description: |
---

Current version (under development) of documentation can be [found here](http://adminfaces.github.io/docs/latest/).

Following is documentation for each released version:

{% for release in site.github.releases %}
  * [{{ release.tag_name }}](http://adminfaces.github.io/docs/{{ release.tag_name }}/index.html) ([PDF](http://adminfaces.github.io/docs/{{ release.tag_name }}/index.pdf))
{% endfor %}
