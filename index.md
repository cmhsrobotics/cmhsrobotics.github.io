---
layout: default
title: Home
---
<section class="hero">
  <h1>{{ site.title }}</h1>
  <p>{{ site.tagline }} &middot; Team {{ site.team_number }}</p>
  <p>Building robots, building people, and spreading STEM in our community.</p>
</section>

<section class="cards">
  <a class="card" href="{{ '/about/' | relative_url }}"><h2>About</h2><p>Our story, mission, and robot.</p></a>
  <a class="card" href="{{ '/team/' | relative_url }}"><h2>Team</h2><p>Meet our students and mentors.</p></a>
  <a class="card" href="{{ '/results/' | relative_url }}"><h2>Results</h2><p>Competition history by season.</p></a>
  <a class="card" href="{{ '/outreach/' | relative_url }}"><h2>Outreach</h2><p>Our local STEM education work.</p></a>
</section>
