---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  background:
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
  spacing: "3rem"
  margin: 2px
  padding: 2px


sections:
  - block: markdown
    content:
    text: |
      <div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
        <h1>📚 Welcome to Yalin Website</h1>
      </div>
    design:
    columns: '1'
    spacing:
      padding: [0, 0, 0, 0]

  - block: collection
    id: blog
    content:
      title: Recent Blog
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
