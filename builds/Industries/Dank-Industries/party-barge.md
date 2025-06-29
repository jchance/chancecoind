---
title: Party Barges
layout: home
parent: Dank Industries
---

# Dank Party Barges
> Why limit your dank to dry land?

---

Dank Party Barges are available for rental!

---

{% for image in site.static_files %}
{% if image.path contains "/ss/dankbarge/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}