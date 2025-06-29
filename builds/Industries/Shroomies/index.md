---
title: Shroomies
layout: home
parent: Industries
---

# Shroomies
> High quality psilosybin products

---
Shroomies sells high quality shrooms, convenient capsules, and other shroom related products.  Don't let the smell turn you away- our staff probably just put on too much patchouli to cover up the stank of their unwashed hippie pits.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/shroomies/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}