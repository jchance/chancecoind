---
title: Envy Emeralds
layout: home
parent: Industries
---

# Envy Emeralds
> You'll be green with envy.

---

Envy Emerald retail locations sell all manner of emerald in various cuts and carats.   All locations feature a hardened safe for secure emerald storage outside business hours.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/envystore/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}