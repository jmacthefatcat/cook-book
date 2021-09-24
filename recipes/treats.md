---
layout: home
---

  <div class="cb-grid">
    {% for treat in site.treats %}
    <a href="{{ treat.url | relative_url }}">
      <div class="frame">
        <img src="{{ "assets/imgs/" | relative_url}}{{ treat.picture }}-small.jpg">
      </div>
      <span class="text-uppercase"><b>{{ treat.title }}</b></span>
    </a>
    {% endfor %}
  </div>
