---
layout: page
title: Research
tagline:
---


(Click the image to read more about our case studies)

To test the feasibility and generic applicability of the proposed framework, methods and models by applying them to case studies in typical urban contexts. Case studies in three typical urban contexts are designed against four main criteria: (1) representing varied spatiotemporal scales; (2) representing different stages of urban development; (3) demonstrating varied data quality; (4) the availability of data sources. 


<p align="left">
  <img width=50% src= /figures/cities/london.png alt="London represents those cities in well-developed countries, and with relatively well-structured mobility datasets. The relevant case study is to model short-term and long-term changes on travel and location choices induced by transport disruptions and new developments.">
</p>


<p align="left">
  <img width=50% src= /figures/cities/shenzhen.png alt="Shenzhen (related to SIMETRI project) represents these cities in newly developed countries with rich datasets but of varying quality. The relevant case study is to model mid-term changes in location choices induced by transport infrastructure development. ">
</p>


<p align="left">
  <img width=50% src= /figures/cities/nairobi.png alt="Nairobi represents those cities in developing countries facing data poverty issues but needing formal urban planning urgently. An example application will be developed as mapping dynamic urban space for long-term strategic planning of natural hazard scenarios.">
</p>


More case studies will be added along we developing our project. 



### Latest Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
