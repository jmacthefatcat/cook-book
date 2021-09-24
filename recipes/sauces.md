---
layout: home
---

  <div class="cb-grid">
    {% for sauce in site.sauces %}
    <a href="{{ sauce.url | relative_url }}">
      <div class="frame">
        <img src="{{ "assets/imgs/" | relative_url}}{{ sauce.picture }}-small.jpg">
      </div>
      <span class="text-uppercase"><b>{{ sauce.title }}</b></span>
    </a>
    {% endfor %}
  </div>
