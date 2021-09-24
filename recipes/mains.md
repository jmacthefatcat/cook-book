---
layout: home
---

  <div class="cb-grid">
    {% for main in site.mains %}
    <a href="{{ main.url | relative_url }}">
      <div class="frame">
        <img src="{{ "assets/imgs/" | relative_url}}{{ main.picture }}-small.jpg">
      </div>
      <span class="text-uppercase"><b>{{ main.title }}</b></span>
    </a>
    {% endfor %}
  </div>
