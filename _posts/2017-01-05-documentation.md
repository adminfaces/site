---
layout: default
img: docs.jpg
category: Documentation
id: documentation
title: Documentation
description: |
---

Current version (under development) of documentation can be [found here]({{site.baseurl}}/docs/latest/.

Following is documentation for each released version:

{% for release in site.github.releases %}
  * [{{ release.tag_name }}]({{site.baseurl}}/docs/{{ release.tag_name }}/index.html) ([PDF]({{site.baseurl}}/docs/{{ release.tag_name }}/index.pdf))
{% endfor %}
