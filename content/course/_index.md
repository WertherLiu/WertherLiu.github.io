---
title: Course
summary: My courses
type: landing
page_type: section
design:
  # Section spacing
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: These are some of my work 
      text:  
      sort_by: 'Date'
      sort_ascending: false  
      filters:
        custom:
          - field: page_type
            value: [section, subpage]
        folders:
          - course
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
