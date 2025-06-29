---
title: Stank-Ass DC
layout: home
parent: Stank-Ass Candle Co
---

# Stank-Ass Distribution Center
> Giving people migranes since 2025

---

{% for image in site.static_files %}
{% if image.path contains "/ss/stankdc/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}