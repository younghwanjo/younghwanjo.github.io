---
layout: archive
permalink: /categories/Travel/
title: "Travel"
author_profile: true
sidebar_main: true
classes: wide
---

{% assign posts = site.categories.Travel %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}