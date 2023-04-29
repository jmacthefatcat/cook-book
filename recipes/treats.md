---
layout: home
---

  <div class="cb-grid">
    {% for treat in site.treats %}
    <a href="{{ treat.url | relative_url }}">
      <div class="frame">
        <img alt="Picture of {{ treat.title }}" src="{{ "assets/imgs/" | relative_url}}{{ treat.picture }}-small.jpg">
      </div>
      <span class="text-lowercase"><b>{{ treat.title }}</b></span>
    </a>
    {% endfor %}
  </div>
