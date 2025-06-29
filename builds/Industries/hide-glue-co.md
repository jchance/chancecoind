---
title: Hide Glue Company
layout: home
parent: Industries
---

# Hide Glue and Horse Products Company
> Like the indigenous peoples of old, we use the whole horse!


---
Located right outside the horse track, Hide Glue is a convenient location to drop off your broken or slow horse for "processing."

---

{% for image in site.static_files %}
{% if image.path contains "/ss/hideglue/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}