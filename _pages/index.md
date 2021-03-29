---
layout: page
title: Home
id: home
permalink: /
---

My name is Edward Orlik. I am a policymaker and artist living and working in Britain. My practice includes painting, video, collage, digital/IRL sculpture, and public service.
I've set up this site as a [[take a rake to it|bit of an experiment]].

## Index of all notes

<ul>
  {% for note in site.notes %}
  <li>
    <a href="{{ note.url }}">>{{ note.title }}</a>
  </li>
  {% endfor %}
</ul>


<style>
  .wrapper {
    max-width: 46em;
  }
</style>
