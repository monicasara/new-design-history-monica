---
override:tags:
  - lcc
  

layout: product
title: Manage materials
description: Managing materials in large and complex cases
pagination:
  data: collections.lcc-manage-materials
  reverse: true
  size: 50
permalink: "lcc/lcc-manage-materials/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"

eleventyComputed:
  eleventyNavigation:
    title: Manage materials
    key: lcc-manage-materials
    excerpt: "{{ description }}"
    parent: lcc
---