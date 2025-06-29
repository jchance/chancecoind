---
title: Phuc Yu Noodle
layout: home
parent: Industries
---

# Phuc Yu Noodle
> You like noodle?  Then Phuc Yu!

---

{% for image in site.static_files %}
{% if image.path contains "/ss/phucyu/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}