---
title: Chance Cabin
layout: home
parent: Residences
---

# Chance Cabin
> A Rustic Escape

---

Chance Cabin is a warm and inviting cabin on the outskirts of Spawn City.   

The prepper basement features ample food and supply storage to weather social disorder and a private JCTA transit line in the sub-basement leads directly to the JCTA Mountain Hub.

**Bonus Trivia:** This is actually the first build I made on this rev.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/cabin/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}