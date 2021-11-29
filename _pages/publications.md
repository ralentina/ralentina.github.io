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

<h2>Books</h2>

{% for post in site.publications reversed %}
{% if post.type == 'book' %}
  {% include archive-single.html %}
{% endif %}
{% endfor %}

<h2>Peer Reviewed Articles</h2>

{% for post in site.publications reversed %}
{% if post.type == 'peer-reviewed' %}
  {% include archive-single.html %}
{% endif %}
{% endfor %}

<h2>Other Publications</h2>

{% for post in site.publications reversed %}
{% if post.type == 'other' %}
  {% include archive-single.html %}
{% endif %}
{% endfor %}

