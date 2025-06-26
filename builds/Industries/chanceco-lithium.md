---
title: ChanceCo Lithium
layout: home
parent: Industries
---

# ChanceCo Lithium
> We put the dirty in "clean energy"

---

Everybody thinks batteries are clean energy, but the truth is the process to extract lithium from the earth is one of the most invasive and dirtiest mining methods where millions of gallons of water are used to pump a lithium slurry out of a mine, spread out to dry in giant pools, and then scooped up and dried for use in industrial battery production.

I tried to represent that with a large open pit mine, slurry pumps, drying pools, and industrial ovens.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/lithium/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}