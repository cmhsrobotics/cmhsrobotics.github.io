---
layout: page
title: Our Team
permalink: /team/
---
<div class="cards">
{% for m in site.data.members %}
  <div class="card">
    {% if m.photo %}<img src="{{ m.photo | relative_url }}" alt="{{ m.name }}">{% endif %}
    <h2>{{ m.name }}</h2>
    <p class="meta">{{ m.role }}{% if m.grade %} &middot; Grade {{ m.grade }}{% endif %}</p>
    <p>{{ m.bio }}</p>
  </div>
{% endfor %}
</div>
