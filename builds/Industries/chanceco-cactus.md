---
title: ChanceCo Cactus
layout: home
parent: Industries
---

# ChanceCo Cactus Growers LLC
> You know, for if you're in to prickly plants or green dye.

---

It's the desert.  We grow cactus in big-ass greenhouses and then ship them to places that want em'.  Its pretty cut and dry really.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/cactus/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}