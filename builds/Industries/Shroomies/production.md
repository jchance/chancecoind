---
title: Shroomies Production Facility
layout: home
parent: Shroomies
---

# Shroomies Production Facilities
> High quality psilosybin products

---

Shroomies taps its high quality psilosybin directly from the source on Mushroom Island and then pumps it back to Mesa City for product production and packaging.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/shroomiesdc/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}