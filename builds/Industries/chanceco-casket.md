---
title: ChanceCo Casket
layout: home
parent: Industries
---

# ChanceCo Casket Company Inc.
> Ask about our lifetime warranty!

---

ChanceCo Casket Company specializes in handcrafting high-end death accessories out of the cheapest bamboo we can grow next door at ChanceCo Bamboo Inc.  Then we lovingly spraypaint it fancy colors and charge your grieving family extra!

*Looking for funeral services?  Head on down to Bard's Funeral Parlor in Spawn City, a CCCI affiliate partner!*

---

{% for image in site.static_files %}
{% if image.path contains "/ss/casket/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}