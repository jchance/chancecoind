---
title: Badlands Tower
layout: home
parent: ChanceCo Telecom
---

# ChanceCo Telecom Badlands Tower
> its a big-ass tower bro.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/tower/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}