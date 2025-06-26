---
title: Power
layout: home
parent: ChanceCo Nuclear
---

# ChanceCo Nuclear Power Plant
> Because windmills are stupid

---

ChanceCo Nuclear Power Plant powers all the industries and facilities in and around Mesa City and provides the residents with safe, polution-free power.

**The plant features:**

1.  2 Reactor Cores
2.  2 Steam Cooling Towers + Pump Facilities
3.  Turbine Hall with redundant turbines for both reactor cycles
4.  On-Site Spent Fuel Cooling Pool

---

{% for image in site.static_files %}
{% if image.path contains "/ss/power/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}