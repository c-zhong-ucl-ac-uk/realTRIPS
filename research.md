---
layout: page
title: Research
tagline:
---

To test the feasibility and generic applicability of the proposed framework, methods and models by applying them to case studies in typical urban contexts. Case studies in three typical urban contexts are designed against four main criteria: (1) representing varied spatiotemporal scales; (2) representing different stages of urban development; (3) demonstrating varied data quality; (4) the availability of data sources. 

---

<div class="tip" markdown="1">

<img align="left" width="150" height="100" src="/figures/cities/london.png">
London represents those cities in well-developed countries, and with relatively well-structured mobility datasets. The relevant case study is to model short-term and long-term changes on travel and location choices induced by transport disruptions and new developments. <a href="/london.md">[read more...]</a>                  
</div>

---

<div class="tip" markdown="1">

<img align="left" width="150" height="100"  src="/figures/cities/shenzhen.png">
Shenzhen (related to SIMETRI project) represents these cities in newly developed countries with rich datasets but of varying quality. The relevant case study is to model mid-term changes in location choices induced by transport infrastructure development. <a href="/shenzhen.md">[read more...]</a> 

</div>

---

<div class="tip" markdown="1">

<img align="left" width="150" height="100"  src="/figures/cities/nairobi.png">
Nairobi represents those cities in developing countries facing data poverty issues but needing formal urban planning urgently. An example application will be developed as mapping dynamic urban space for long-term strategic planning of natural hazard scenarios. <a href="/nairobi.md">[read more...]</a> 

</div>

---
More case studies will be added along we developing our project. 



### Latest Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
