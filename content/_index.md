---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
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
          filename: stacked-peaks1.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        ​In my research, I focus on advancing deep learning methodologies for hyperspectral image analysis, particularly in the realms of classification and image fusion. Hyperspectral imaging captures a wide spectrum of light across numerous contiguous bands, providing detailed spectral information for each pixel. This richness facilitates precise identification and characterization of materials in a scene, making it invaluable in fields and applications.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'

  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation

  # Removed 'news' section below
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     page_type: post
  #     count: 5
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     offset: 0
  #     order: desc
  #   design:
  #     view: date-title-summary
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
