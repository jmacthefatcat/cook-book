---
layout: home
---

  <div class="cb-grid">
    {% for side in site.sides %}
    <a href="{{ side.url | relative_url }}">
      <div class="frame">
        <img src="{{ "assets/imgs/" | relative_url}}{{ side.picture }}-small.jpg">
      </div>
      <span class="text-uppercase"><b>{{ side.title }}</b></span>
    </a>
    {% endfor %}
  </div>
