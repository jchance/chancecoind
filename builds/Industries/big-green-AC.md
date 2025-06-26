---
title: Big Green AC
layout: home
parent: Industries
---

# Big Green AC and HVAC
> Is your building hot?  Get yourself a Big Green AC!

---

Just about every city build I've done has a green AC unit on the roof as a design detail so I decided to make Big Green AC in the Spawn City industrial area.

**BGAC is an automated factory that features robot assembly:**

1.  Raw steel comes in from [ChanceCo Steel](/builds/Industries/chanceco-steel)
2.  Cactus gets shipped in from [ChanceCo Cactus](/builds/Industries/chanceco-cactus) and ground up into green paint
3.  Robots!
4.  Complete AC unit comes out the other end.


---

{% for image in site.static_files %}
{% if image.path contains "/ss/bgac/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}