---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Journal Publications

{% assign journals = site.publications | where: "category", "journal" | sort: "date" | reverse %}
{% for post in journals %}
  {% include archive-single.html %}
{% endfor %}

## Conference Publications

{% assign conferences = site.publications | where: "category", "conference" | sort: "date" | reverse %}
{% for post in conferences %}
  {% include archive-single.html %}
{% endfor %}
