---
layout: page
title: STEM Outreach
permalink: /outreach/
---
Describe the team's commitment to local STEM education here.

{% for o in site.data.outreach %}
<article class="card">
  <h2>{{ o.title }}</h2>
  <p class="meta">{{ o.date }} &middot; {{ o.location }} &middot; Reached: {{ o.reach }}</p>
  <p>{{ o.description }}</p>
</article>
{% endfor %}

## Get Involved
Want us to visit your school or event? Email us at <a href="mailto:{{ site.email }}">{{ site.email }}</a>.
