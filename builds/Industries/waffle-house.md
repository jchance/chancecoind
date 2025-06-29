---
title: Waffle House
layout: home
parent: Industries
---

# Waffle House
> "Fuck you, I'm smoking.  Make your own waffle."

{: .danger-title }
> LIKE REAL LIFE, WAFFLE HOUSE IS A PVP ZONE
>
> Unlike the rest of Creative, the Waffle House building and parking lot are a PVP zone.  You can be attacked by other players on Waffle House property.

---

>“Is the Waffle House universally awesome? It is indeed, marvelous, an irony-free zone where everything is beautiful and nothing hurts; where everybody, regardless of race, creed, color, or degree of inebriation, is welcomed—its warm yellow glow a beacon of hope and salvation, inviting the hungry, the lost, the seriously hammered all across the South to come inside. A place of safety and nourishment. It never closes, it is always faithful, always there for you.”
>
>**― Anthony Bourdain, World Travel: An Irreverent Guide**

---

{% for image in site.static_files %}
{% if image.path contains "/ss/wh/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}