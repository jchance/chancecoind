---
title: Trap House
layout: home
parent: Residences
---

# 2Chainz Trap House
> Based on 1530 Howell Mill Rd in Atlanta, GA.

---

This joke build is based on [2Chainz pink Trap House](https://www.fox5atlanta.com/news/2-chainz-wants-to-save-pink-trap-house-in-atlanta){:target="_blank"} that was at 1530 Howell Mill Rd in Atlanta, GA.  It has since been demolished.



---

{% for image in site.static_files %}
{% if image.path contains "/ss/traphouse/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}