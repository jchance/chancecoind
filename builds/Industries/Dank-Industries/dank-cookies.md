---
title: Dank Cookie Co
layout: home
parent: Dank Industries
---

# Dank Cookie Co
> Cannibis Infused Cookies Baked Fresh Daily

---

{% for image in site.static_files %}
{% if image.path contains "/ss/dankcookie/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}