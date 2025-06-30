---
title: City Hall
layout: home
parent: Mesa City
---

# Mesa City - City Hall
> It's even got working floodgates!

{% include warp.md warp="MesaCity" %}

---

Mesa City's City Hall building is based loosely on the [Hawaii State Capitol in Honolulu](https://en.wikipedia.org/wiki/Hawaii_State_Capitol){:target="_blank"} and features the JCTA badlands transit hub in the building basement.  

In the open air courtyard there is a warp board that gives fast access to other points of interest in the badlands.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/mesacityhall/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}