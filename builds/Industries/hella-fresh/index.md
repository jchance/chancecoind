---
title: Hella Fresh!
layout: home
parent: Industries
---

# Hella Fresh!
> Modern Grocery Chain

The Hella Fresh! family of brands includes Hella Fresh! full service grocery stores, [Hella Fresh Express!](/builds/Industries/hella-fresh/hella-fresh-express) convenience stores, [Sorta Fresh?](/builds/Industries/hella-fresh/sorta-fresh) discount stores for low income markets, and a full service [distribution center](/builds/Industries/hella-fresh/hella-fresh-dc) in Mesa City and [HQ building](/builds/Industries/hella-fresh/hella-fresh-hq) in Spawn City.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/hellafresh/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}