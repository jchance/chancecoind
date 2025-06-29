---
title: Red Mesa Prison
layout: home
parent: Industries
---

# Red Mesa Prison
> a for-profit prison providing cheap prison labor to a range of ChanceCo Industries.

{% include warp.md warp="prison" %}

---

Red Mesa Prison has 3 general population cell blocks, a minimum security wing, death row and execution chamber, infirmary, creamatorium, workshop, cafeteria, laundry, and more.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/prison/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}