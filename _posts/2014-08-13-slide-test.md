---
layout: post
title: slide test
kind: slideshow
slides:
- url: bg08.svg
- url: bg11.svg
- url: bg06.svg
---

{% if page.slides %}
<div class="slick-slideshow">
{% for sl in page.slides %}
    <div><img src="{{ site.baseurl }}/kdk-assets/imgs/{{ sl.url }}" /></div>
{% endfor %}
</div>
{% endif %}
