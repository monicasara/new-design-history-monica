---
override:tags: []
layout: product
title: Large and complex cases
description: Large and complex cases
pagination:
  data: collections.lcc
  reverse: true
  size: 50
permalink: "lcc/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    title: Large and complex cases
    key: lcc
    excerpt: "{{ description }}"
    parent: Home
---