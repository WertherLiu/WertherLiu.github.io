---
title: Course
summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: money-and-banking
    content:
      title: Money and Banking
      filters:
        folders:
          - course/Money&Banking
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: ai
    content:
      title: AI
      filters:
        folders:
          - course/AI
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: topology
    content:
      title: Topology
      filters:
        folders:
          - course/Topology
    design:
      view: article-grid
      columns: 2
---
