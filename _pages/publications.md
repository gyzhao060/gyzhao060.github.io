---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for publi in site.data.publist %}

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.date }},  {{ publi.journal }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
 
{% endfor %}

For a full list of my publications, please visit my [ORCID page](https://orcid.org/0000-0002-4417-1659).
