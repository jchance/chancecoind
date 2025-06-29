---
title: Sorta Fresh
layout: home
parent: Hella Fresh!
---

# Sorta Fresh
> Because the poors need to eat too.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/sortafresh/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}