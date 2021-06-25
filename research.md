---
layout: page
title: Research
tagline:
---

London represents those cities in well-developed countries, and with relatively well-structured mobility datasets.
Our goal is to model short-term and long-term changes on travel and location choices induced by transport disruptions and new developments.
<figure style="width:70%; padding:10px;" >
	<a href="https://c-zhong-ucl-ac-uk.github.io/realTRIPS/london.html">
		<img src="{{site.baseurl}}/figures/cities/london.png"/>
	</a>
</figure>



Shenzhen (related to SIMETRI project) represents these cities in newly developed countries with rich datasets but of varying quality. 
To model mid-term changes in location choices induced by transport infrastructure development. 
<figure style="width:70%; padding:10px;" >
	<a href="https://c-zhong-ucl-ac-uk.github.io/realTRIPS/shenzhen.html">
		<img src="{{site.baseurl}}/figures/cities/shenzhen.png"/>
	</a>
</figure>


Nairobi represents those cities in developing countries facing data poverty issues but needing formal urban planning urgently. 
An example application will be developed as mapping dynamic urban space for long-term strategic planning of natural hazard scenarios.

<figure style="width:70%; padding:10px;" >
	<a href="https://c-zhong-ucl-ac-uk.github.io/realTRIPS/nairobi.html">
		<img src="{{site.baseurl}}/figures/cities/nairobi.png"/>
	</a>
</figure>



### Latest Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
