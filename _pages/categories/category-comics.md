---
title: "Comics"
layout: archive
permalink: categories/comics
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.Comics %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
