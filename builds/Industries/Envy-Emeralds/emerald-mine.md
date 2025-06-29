---
title: Emerald Mine
layout: home
parent: Envy Emeralds
---

# Envy Emerald Mine
> You'll be green with envy.

---

Envy Emerald Mine is located in Mesa City.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/envymine/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}