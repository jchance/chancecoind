---
title: JC's Truck Service
layout: home
parent: Industries
---

# JC's Truck Service and Diesel Mechanic
> Where a dude named Bubba fixes your big rig.

---

Located on the outskirts of Mesa City, JC's Truck Service is a full service mechanic for 18-wheelers, delivery trucks, industrial equipment, and other diesel powered trucks.

The parking lot also serves as a convenient centralized yard for all the ChanceCo industry vehicle designs that I can cut and paste from as needed.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/truckservice/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}