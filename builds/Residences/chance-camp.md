---
title: Chance Camp
layout: home
parent: Residences
---

# Chance Camp
> Where we go to avoid the poors.

---

>“I went to the woods because I wished to live deliberately, to front only the essential facts of life, and see if I could not learn what it had to teach, and not, when I came to die, discover that I had not lived. I did not wish to live what was not life, living is so dear; nor did I wish to practise resignation, unless it was quite necessary. I wanted to live deep and suck out all the marrow of life, to live so sturdily and Spartan-like as to put to rout all that was not life, to cut a broad swath and shave close, to drive life into a corner, and reduce it to its lowest terms...”
>
>**― Henry David Thoreau**

Following the path in the woods past the crazy prepper tent leads to a secret rail connection to the JCTA Mountain Hub.

---

{% for image in site.static_files %}
{% if image.path contains "/ss/camp/" %}
<a href="{{ image.path }}"><img src="{{ image.path }}" alt="image" /></a>
{% endif %}
{% endfor %}