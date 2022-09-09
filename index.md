---
layout: default
title: Welcome
nav_order: 1
description: "Welcome"
permalink: /
---

# Welcome to the UCL PONDernet (internal web pages)

[POND](http://pond.cs.ucl.ac.uk) stands for Progression Of Neurodegenerative Disease, but we do more than that.

We are part of the the UCL [Centre for Medical Image Computing](https://www.ucl.ac.uk/medical-image-computing) (CMIC) in the Department of Computer Science (CS).

This is mostly an internal website for POND procedures, tutorials, and practices --- some of which will be useful to CMIC, CS, and beyond. If you're based at UCL, get involved and contribute to the community with suggestions, documentation requests, etc., by submitting an [issue](https://github.com/noxtoby/noxtoby.github.io/issues) or a [Pull Request](https://github.com/noxtoby/noxtoby.github.io/pulls).

If you are a POND member and are documenting one of your tools/processes, please create your documentation according to the [documentation guidelines](docs/Contributing/contributing) and submit a [Pull Request](https://github.com/noxtoby/noxtoby.github.io/pulls), so it can be reviewed and added to the site.


#### Thank you to all contributors to the UCL PONDernet
<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


This documentation website was created using [Jekyll and Github pages](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll); the template is [`just-the-docs`](https://just-the-docs.github.io/just-the-docs/).
