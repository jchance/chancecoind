---
title: Dollar General
layout: home
parent: Industries
---

# Dollar General
> Overpriced crap right around the corner!

---

With a convenient Redbox location right out front, Dollar General is cluttered, overpriced, and understaffed with stock filling the isles... just like a real Dollar General!

---

{% for image in site.static_files %}
{% if image.path contains "/ss/dg/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}