---
layout: post
title: Astrocraft reaction words
date: 2023-09-23 12:42 +0200
tags: [minecraft, astrocraft]                   #tags should always be lowercase
---

{% assign my_array = "
Obsidian, 
Aurora, 
Redstone, 
Feed" | newline_to_br| split: ", " %}

{{ my_array | sort_natural | join: ", " }}