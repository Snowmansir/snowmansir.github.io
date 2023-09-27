---
layout: post
title: Astrocraft reaction words
date: 2023-09-23 12:42 +0200
tags: [minecraft, astrocraft]                   #tags should always be lowercase
---

{% assign reaction = "
Obsidian,
Aurora,
Redstone,
Feed,
Jupiter,
Coal,
Hierarchy," | split: "," %}

{{ reaction | sort_natural | join: ",  "}}
{% for member in reaction %}
{% endfor %}