---
title: Testimonials
layout: default
---

{% for t in site.data.testimonial limit:2 %}
{{ t.testimonial }}
{{ t.author | upcase }}
{% endfor %}
