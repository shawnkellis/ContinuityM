---
layout: default
title: "ContinuityM"
description: "Technical essays by Shawn K. Ellis exploring digital migration, AI continuity, and the long-term evolution of intelligence and infrastructure."
---

<section>
  <h2>Essays</h2>
  <ul class="essay-list">
    {% for essay in site.essays %}
      <li>
        <a href="{{ essay.url | relative_url }}">{{ essay.title }}</a>
      </li>
    {% endfor %}
  </ul>
</section>
