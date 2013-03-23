---
layout: page
title: Open Governance
tagline: an open source framework
---
{% include JB/setup %}

### Recent news

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### What is drakkr?

__Every organization which use Open Source components needs an Open Source Governance__.

The usage of Open Source is motivated by __multiple vectors__ such as:

* Financial
* Technical
* Ethics...

Nevertheless __multiple risks__ are identified:

* License terms
* Security flaws
* Project extinction...

Recurrent __questionings__ appears as the maturity of governance evolves:

* What would be the best component for a specific usecase?
* Which element should be analyzed to determine a project's strategy?
* What is the ROI expected with the adoption of an Open Source Component?

_Drakkr is a toolbox designed to help organizations in their integration and management of Open Source Components through best practices recommendations, suggested processes & enterprise organization and Open Source tools._

![Drakkr schema](https://raw.github.com/drakkr/drakkr/master/Manifesto/en/Images/drakkr-schema_en.png)

Based on several proven Open Source tools and methodologies such as [QSOS](http://www.qsos.org), [Open Source Cartouche](http://www.opensourcecartouche.org), [ECOS](http://www.drakkr.org/ecos/) or [FLOSC](http://www.drakkr.org/flosc/).

Still in intensive development, Drakkr is evolving quickly and will be released soon.
