---
title: Course
summary: My courses
type: landing

cascade:
  - _target:
      kind: section
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: course
    content:
      title: course
      filters:
        folders:
          - course
        types:
          - section
        exclude_featured: false
        exclude_pages: true
    design:
      view: article-grid
      columns: 2
---
