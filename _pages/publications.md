---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Published works

```python
import ads
import numpy as np
import json
import os

# add token
ads.config.token = "J5HObK5cd9tIqHYNTSqQ5xDspXidwyMZbNw07cbG"

# do query
fl = ['id', 'bibcode', 'citation_count']
rows = 2000
max_pages = 1
papers = ads.SearchQuery(author="picogna", sort="citation_count", fl=fl, rows=rows, max_pages=max_pages)
papers.execute()
bibcodes = [i.bibcode for i in papers.articles]

tot_citations = 0
# loop on papers
for paper in papers:
    # get bibindex
    citations = paper.citation_count
    if(citations is None):
        citations = 0
    # add to total citations
    tot_citations += citations

def get_indices_of_papers(metrics):
    """
    Convert the metrics into a format that is easier to work with. Year-ordered
    numpy arrays.
    """
    h = []
    y = list(metrics['time series']['h'].keys())
    y.sort()
    for i in range(len(y)):
        k = y[i]
        h.append(metrics['time series']['h'][k])
    h = np.array(h)
    return h

# Collect the metrics from the API
mq = ads.MetricsQuery(bibcodes=bibcodes)
metrics = mq.execute()

# Indices
h = get_indices_of_papers(metrics)

print("Total citations: ", tot_citations, ", h index: ", h[-1])
```

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
