---
title: "위인 이야기"
layout: archive
permalink: categories/greatman
auther_profile: true
sidebar_main: true
---

{% assign posts = site.categories.greatman%}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}