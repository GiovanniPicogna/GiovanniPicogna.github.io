---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Published works

### Disk evolution and dispersal
---

{% for post in site.publications reversed %}
  {% if post.PublicationStatus == 'Published' and post.tags contains 'photoevaporation' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

### Dust evolution
---

{% for post in site.publications reversed %}
  {% if post.PublicationStatus == 'Published' and post.tags contains 'dust evolution' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

### Planet formation in binary stars
---

{% for post in site.publications reversed %}
  {% if post.PublicationStatus == 'Published' and post.tags contains 'binary stars' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Submitted works

{% for post in site.publications reversed %}
  {% if post.PublicationStatus == 'Submitted' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Works in preparation

{% for post in site.publications reversed %}
  {% if post.PublicationStatus == 'In preparation' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
