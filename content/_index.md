---
# Leave the homepage title empty to use the site title
title: ''
date: 2026-09-14
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: '📊 Data Science & AI Projects'
      subtitle: ''
      text: |-
        Leveraging an interdisciplinary background across Data Science, Business Administration (MBA), and Clinical Psychology (MA) to build human-centered AI models, machine learning pipelines, and predictive data analytics solutions.

        Focused on Natural Language Processing (NLP), intent classification systems, predictive modeling, and data-driven process optimization.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Projects & Applications
      text: ''
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
---
