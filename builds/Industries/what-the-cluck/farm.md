---
title: Chicken Farm
layout: home
parent: What the Cluck?
---

# What the Cluck? Chicken Farm
> What do they do with all the chicken shit?

---

Located in Mesa City, WTC? Farm grows high quality antibiotoic free (but loaded with steroids) chicken and chicken products.  These chickens got bigger breasts than your mom!

---

{% for image in site.static_files %}
{% if image.path contains "/ss/wtcdc/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}