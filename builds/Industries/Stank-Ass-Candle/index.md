---
title: Stank-Ass Candle Co
layout: home
parent: Industries
---

# Stank-Ass Candle Co
> Strong Smelling Candles

---

Four stories of migrane inducing candles that smell so strong you might get nose cancer.  Retail locations feature our innovative Sniffing Room for trying out new scents.

*Ask about our "Stank of the Month Club!"*

---

{% for image in site.static_files %}
{% if image.path contains "/ss/stank/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}