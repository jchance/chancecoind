---
title: ChanceX
layout: home
parent: Industries
---

# ChanceX
> Its literally rocket science.

---

### Things ChanceX is good at:

1.  Launching Rockets without blowing them up

### More Facts:

As a bonus, the ChanceX founder doesn't buy social media platforms and run them in to the ground, impregnate 12 different women and name the kids weird things, make up new bullshit products like Hyperloop when the stock price dips, give stiff-arm salutes at political rallies, or take excessive tranquilizers.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/chancex/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}