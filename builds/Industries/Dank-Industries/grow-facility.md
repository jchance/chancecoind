---
title: Dank Grow Op
layout: home
parent: Dank Industries
---

# Dank Industries Growing Operations Center
> Where we grow the sticky-icky

---

Dank Industries Growing Operations Center grows thousands of pounds of jazz cabbage for sale around Creative in Dank Industries Dispensaries and for use in Dank Cookie recipes.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/dankdc/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}