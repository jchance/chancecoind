---
title: Mesa City
layout: home
---

# Mesa City
> Another Fine ChanceCo Industries Community

{% include warp.md warp="MesaCity" %}

---

## Overview

Built in the badlands biome where most players don't care to build, Mesa City was created so I wouldn't fill up Spawn City and leave some plots for the other players :P

Red Sandstone themed, Mesa City is the official "ChanceCo Company Town" with all aspects of life controlled by the benevolent dictatorship of the ChanceCo Industries board of directors.

## Region Map

[![Badlands region west of Spawn](/assets/mesa-city-map.png)](/assets/mesa-city-map.png)

---

---

{% for image in site.static_files %}
{% if image.path contains "/ss/mesacity/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}