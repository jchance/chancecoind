---
title: Doomsday Bunker
layout: home
parent: Residences
---

# Chance Doomsday Bunker
> Everything you need for a good time at the end of the world.

---

The Chance Doomsday Bunker features living spaces, indoor hydroponic farming of various food and "medicinal" crops, ample storage to wait out the end of the world, a heliport, watch tower, and drone launch capabilities to monitor the ChanceCo empire through any apocolypse.

In the sub basement is the JCTA Mountain Hub which links to various other ChanceCo properties and the Mesa City Transit Hub under [City Hall](/builds/MesaCity/city-hall).

---

{% for image in site.static_files %}
{% if image.path contains "/ss/bunker/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}