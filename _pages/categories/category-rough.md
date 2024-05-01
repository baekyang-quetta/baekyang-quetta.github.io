---
title: "Rough"
layout: archive
permalink: categories/rough
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.Rough %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}
