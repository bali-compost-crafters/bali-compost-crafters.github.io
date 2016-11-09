---
title: Testimonials
layout: default
---

{% for t in site.data.testimonial limit:2 %}
<p>"{{ t.testimonial }}"</p>
 <p>- {{ t.author | upcase }} -</p>
{% endfor %}
