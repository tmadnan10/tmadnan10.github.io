---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Fast, scalable and geo- distributed PCA for big data analytics
------
TM Tariq Adnan, Md Mehrab Tanjim, and Muhammad Abdullah Adnan. “Fast, scalable and geo- distributed PCA for big data analytics". Information Systems, 98 (2021): 101710. [Paper] [Code]

UACD: A Local Approach for Identifying the Most Influential Spreaders in Twitter in a Distributed Environment
------
TM Tariq Adnan, Md. Saiful Islam, Md. Tarikul Islam Papon, Sourav Kumar Nath, Muhammad Abdullah Adnan. “UACD: A Local Approach for Identifying the Most Influential Spreaders in Twitter in a Distributed Environment". Article is under review at Social Network Analysis and Mining (SNAM).

#{% for post in site.publications reversed %}
#  {% include archive-single.html %}
#{% endfor %}
