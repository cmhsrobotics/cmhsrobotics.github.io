---
layout: page
title: Competition Results
permalink: /results/
---
{% for s in site.data.results %}
## {{ s.season }}: {{ s.game }}
<table>
  <thead><tr><th>Event</th><th>Result</th><th>Notes</th></tr></thead>
  <tbody>
  {% for e in s.events %}
    <tr><td>{{ e.name }}</td><td>{{ e.result }}</td><td>{{ e.notes }}</td></tr>
  {% endfor %}
  </tbody>
</table>
{% endfor %}
