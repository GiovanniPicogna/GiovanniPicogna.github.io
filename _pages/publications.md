---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

47 refereed publications (9 first-author), 1,300+ citations, h-index 22 (NASA ADS, October 2026).
Full and up-to-date list on [NASA ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0003-3754-1639&sort=date%20desc). Selected papers below.

## Published works

### Numerical methods, codes and machine learning
---

{% for post in site.publications reversed %}
  {% if post.PublicationStatus == 'Published' and post.tags contains 'methods' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

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
