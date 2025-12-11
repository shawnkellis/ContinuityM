---
layout: default
title: "ContinuityM"
description: "Technical essays by Shawn K. Ellis exploring digital migration, AI continuity, and the long-term evolution of intelligence and infrastructure."
---

<section class="hero">
  <h1>ContinuityM</h1>
  <p>Technical essays by Shawn K. Ellis exploring digital migration, AI continuity, and the long-term evolution of intelligence and infrastructure.</p>
</section>

<section class="essay-list">
  <h2>Essays</h2>
  <ul>
    {% for essay in site.essays %}
      <li>
        <a href="{{ essay.url | relative_url }}">
          {{ essay.title }}
        </a>
        <span class="essay-meta">
          {{ essay.date | date: "%Y-%m-%d" }}
        </span>
      </li>
    {% endfor %}
  </ul>
</section>
