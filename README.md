---
layout: default
title: Extra Flags Gallery
---
<link rel="stylesheet" type="text/css" href="README.css" />

<h1>Extra Flags Gallery</h1>

<p>A specialized repository for non-standard, historical, controversial, and alternate history flag designs.</p>

## Flags

<div class="container">
{% for flag in site.data.flags %}
  <div id="flag-{{ flag.code }}">
    <code title="{{ flag.code }}">{{ flag.code }}</code>
    <img src="flags/{{ flag.code }}.svg"/>
    <p>{{ flag.name }}</p>
  </div>
{% endfor %}
</div>
