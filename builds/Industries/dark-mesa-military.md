---
title: Dark Mesa Military Reservation
layout: home
parent: Industries
---

# Dark Mesa Military Reservation
> We got buttons and aren't afraid to push em'

{% include warp.md warp="military" %}

---

Dark Mesa Military Reservation houses the Mesa City nuclear deterent option just in case Spawn City gets all uppity and wants to throw hands.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/military/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}