---
layout: page
title: Home
id: home
permalink: /
---

My name is Edward Orlik. I am a policymaker and artist living and working in Britain. My practice includes painting, video, collage, digital/IRL sculpture, and public service.
I've set up this site as a [[take a rake to it|bit of an experiment]].

## Index of all notes
<br>
<div style="display:block">
<container class="card-stack">
  {% for note in site.notes %}
<div class="card">
  <p>{{note.title}}</p>
</div>
  {% endfor %}
</container>
</div>
