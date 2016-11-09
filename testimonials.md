---
title: Testimonials
layout: default
---

{% for t in site.data.testimonial %}
  *"{{ t.testimonial }}"*
  {{ t.author | upcase }}
{% endfor %}
