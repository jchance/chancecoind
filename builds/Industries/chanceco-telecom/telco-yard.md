---
title: Operations Center
layout: home
parent: ChanceCo Telecom
---

# ChanceCo Telecom Operations Center
> New phone who dis?

---

Not the most exciting build, but was mostly built as an excuse to put together 5 or 6 different telco truck combinations and add a bucket truck.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/telco/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}