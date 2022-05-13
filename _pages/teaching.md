---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
current_semester: "Fall 2022"
---
{% include base_path %}

## {{ page.current_semester }}

{% for post in site.teaching %}
  {% if post.semester == page.current_semester %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Previous Semesters

## @ Old Dominion University

* CS 432/532 - Web Science ([Spring 2018](https://xandernwala.github.io/teaching/2021-fall-cs-432-532)/[2019](https://xandernwala.github.io/teaching/2021-fall-cs-432-532))
