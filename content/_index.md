---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"
  margin: 2px
  padding: 2px


sections:
  - block: markdown
    content:
      title: '📚 Welcome'
      subtitle: ''
      text: |-
            
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: actual
          position: center
          parallax: false
  
  - block: resume-biography-3
    id: Bio
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "I am currently seeking for the admission to Peking University to begin my life as a graudate student. Before that, I graduated from Renmin University in 2024, Economics & Mathematics Dual-Degree Program.You can contact me via email 2020200745@ruc.edu.cn."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false


  - block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders:
          - event
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: card



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

  - block: collection
    id: course
    content:
      title: Course Materials
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: experience
    content:
      title: Experience
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  
  
---
