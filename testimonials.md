---
title: Testimonials
layout: default
---

<div class="row expanded text-center" style="padding-right: 4rem; padding-left: 4rem;">
        {% for t in site.data.testimonial %}
        <p><strong>"{{ t.testimonial }}"</strong></p>
        <p><strong>- {{ t.author}} - </strong></p>
        <hr>
        {% endfor %}
</div>
