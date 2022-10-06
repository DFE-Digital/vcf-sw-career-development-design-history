---
layout: collection
title: Beta phase
description: Beta designs and decision history
pagination:
  data: collections.beta-phase
  reverse: true
  size: 50
permalink: "beta-phase/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
