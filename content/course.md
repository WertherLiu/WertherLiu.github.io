---
title: Course
summary: My courses
type: landing

design:
  # Section spacing
  spacing: '5rem'

sections:
  - block: collection
    id: course
    content:
      title: course
      filters:
        folders:
          - course
        exclude_featured: false
      sort:
        by: weight
        order: asc
    design:
      view: article-grid
      columns: 2
---
