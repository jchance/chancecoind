---
title: Oil Rig
layout: home
parent: ChanceCo Petroleum
---

# ChanceCo Petroleum Off-Shore Oil Rig
> No dolphins were recorded being harmed during the construction of the oil rig.

---

ChanceCo Oil Rig is off the coast of Mesa City and features a oil tanker filling hub, various pumps and storage tanks, rig worker housing and liesure areas, a satelite Hella Fresh! location, and a containerized Paddy Murphy's location for employee relaxation.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/rig/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}