---
title: Tofu Mart
layout: home
parent: Industries
---

# Tofu Mart
> Marting11's vegan sadness option.

---

Tofu Mart features Marting11's iconic color CMYK color scheme and exactly 3 tofu products:

1.  Tofu
2.  Smoked Tofu
3.  Tofurkey

---

{% for image in site.static_files %}
{% if image.path contains "/ss/tofu/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}