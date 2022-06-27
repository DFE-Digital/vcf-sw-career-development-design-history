---
layout: collection
title: Alpha phase
description: Alpha designs and decision history
pagination:
  data: collections.alpha-phase
  reverse: true
  size: 50
permalink: "alpha-phase/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
