---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
    - /resume
---

{% include base_path %}

# Education

-   Ph.D in Rochester, Rochester Institute of Technology, 2028 (expected)
-   M.S. in Rochester, Rochester Institute of Technology, 2023
-   B.S. in Boulder, University of Colorado, 2019

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
