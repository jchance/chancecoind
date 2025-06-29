---
title: Refinery
layout: home
parent: ChanceCo Petroleum
---

# ChanceCo Petroleum Refinery
> Black Gold

{% include warp.md warp="refinery" %}

---

ChanceCo Refinery is connected to ChanceCo Port for direct ocean tanker offload and features bulk storage tanks for raw crude, pump houses and distilation columns for breaking down the crude in to secondary products, and finished product storage tanks.

Support buildings include a shower / locker room for employees, a control tower, administrative offices, and a trucker office for tanker drivers while filling their loads for delivery.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/refinery/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}