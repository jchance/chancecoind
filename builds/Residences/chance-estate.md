---
title: Chance Estate
layout: home
parent: Residences
---

# Chance Estate and Yacht
> Where we go to avoid the poors.

---

The Chance Estate is a modern mansion on the intercostal waterway and features a gallery hall, commercial kitchen, full-service garage, boat house, indoor sauna and hot tub, outdoor pool, multiple guest rooms, and a full-electric catamaran yacht moored out back.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/estate/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}