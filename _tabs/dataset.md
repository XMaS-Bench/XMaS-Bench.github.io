---
layout: post
title: Datasets
order: 1
icon: fa fa-database
toc: true
---

## Oracle Dataset

Here you can provide a detailed description of your datasets.

<div id="post-list" class="flex-grow-1 px-xl-1">
  {% assign oracle_posts = site.posts | where: "categories", "Oracle" %}
  {% for post in oracle_posts %}
    {% include post-card.html post=post %}
  {% endfor %}
</div>

## Benchmark Dataset
