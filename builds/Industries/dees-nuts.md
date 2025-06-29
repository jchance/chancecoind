---
title: Dee's Nuts
layout: home
parent: Industries
---

# Dee's Fancy Domestic and Imported Nuts
> Feeling peckish?  Put Dee's Nuts in your mouth!

---

{% for image in site.static_files %}
{% if image.path contains "/ss/dees/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}