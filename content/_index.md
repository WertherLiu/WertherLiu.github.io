---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      title: '📚 Welcome'
      subtitle: ''
      text: |-
        This is my website!  
        I am currently seeking for the admission to Peking University to begin my. I graduated from Renmin University in 2024, Economics & Mathematics Dual-Degree Program. In my free time, I like to read history books and watch Harry Potter movies. You can contact me via email 2020200745@ruc.edu.cn.😃
    design:
      columns: '1'
      background:
        image:
          # Name of image in `assets/media/`.
          filename: background.jpg
          # Apply image filters?
          filters: true
          # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
          brightness: 0.6
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
    
  - block: resume-biography-3
    id: Bio
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "This is yalin's website"
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
      title: Precious Photos
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: experience
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  
  
---
