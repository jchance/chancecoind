---
title: Chancebo Observatory
layout: home
parent: Industries
---

# Chancebo Observatory Radio Telescope
> The largest radio telescope on nerd.nu

{% include warp.md warp="BigDish" %}

---

Chancebo radio observatory searches the Minecraft aether for signs of intelligent life.  Sadly, our efforts thus far have been in vain.

It has seemed to attract some extra terrestrial attention just outside the gates though.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/chancebo/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}