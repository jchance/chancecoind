---
title: Dispensaries
layout: home
parent: Dank Industries
---

# Dank Industries Dispensary
> Its for my cataracts officer, I swear!

---
With several convenient locations across Creative, Dank Industries Dispensaries sell medical marijuana and THC products.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/dankind/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}