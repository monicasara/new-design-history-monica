---
override:tags: []
layout: product
title: Disproportionality
description: A service for to monitor disproportionality in the use of language
pagination:
  data: collections.dispro
  reverse: true
  size: 50
permalink: "dispro/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    title: Disproportionality
    key: dispro
    excerpt: "{{ description }}"
    parent: Home
---
