---
layout: photolist
title: Practicals
menu: true
---


# Practicals


{% assign practicals = (site.data.assignments | where: "selected", "y") %}
{% for practical in practicals %}
{% include assignment.html lecture=practical %}
{% endfor %}

