---
layout: page
title: Tutorials
permalink: /tutorials/
show-in-nav: true
---

# Tutorials
---

<div class="page-section">
  <div class="tutorials-grid card-grid">
    {% for tutorial in site.tutorials %}
      <div class="card-grid__card">
        <h3>{{ tutorial.title }}</h3>
        <p>{{ tutorial.abstract }}</p>
        <div class="card-grid__card__footer">
          <h4>Read more</h4>
          <a href="{{ tutorial.url }}" class="card-grid__card__footer__next-btn">
            <i class="fas fa-chevron-right"></i>
          </a>
        </div>
      </div>
    {% endfor %}
  </div>
</div>