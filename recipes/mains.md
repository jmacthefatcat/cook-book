---
layout: home
---

  <div class="cb-grid">
    {% for main in site.mains %}
    <a href="{{ main.url | relative_url }}">
      <div class="frame">
        <img alt="Picture of {{ main.title }}" src="{{ "assets/imgs/" | relative_url}}{{ main.picture }}-small.jpg">
      </div>
      <span class="text-lowercase"><b>{{ main.title }}</b></span>
    </a>
    {% endfor %}
  </div>
