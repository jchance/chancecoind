---
title: What the Cluck?
layout: home
parent: Industries
---

# What the Cluck? Smoked Chicken
> Get Clucked!

---

*What the Cluck?* sells affordable whole and half smoked chickens for consumption by humans.  

---

{% for image in site.static_files %}
{% if image.path contains "/ss/wtc/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}