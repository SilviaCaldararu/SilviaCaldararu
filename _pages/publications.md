---
title: "Plant Ecology Modelling group - Publications"
layout: gridlay
excerpt: "Plant Ecology Modelling group  -- Publications."
sitemap: false
permalink: /publications/
---


# Publications


{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
