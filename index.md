---
layout: default
title: Releases
---

# Latest Releases

{% for release in site.github.releases %}
- [{{ release.name }}]({{ release.html_url }}) - {{ release.published_at }}
{% endfor %}
