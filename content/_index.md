---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: |-
        I am a **PhD student in the Cancer Systems Pharmacology team of the U1331 Computational Oncoly research unit at Institut Curie**, funded by Inserm, Inria, and Institut Curie.

        As a PhD student in applied mathematics for cancer biology, I develop and study **model learning methods** for discovering and identifying dynamic systems from experimental data.

        My work focuses in particular on the circadian analysis of omics data and the inference of parsimonious differential models, with applications to the **circadian clock, the immune system, and the optimization of cancer treatments**.
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV (ENG)
        url: uploads/CV_Clemence_Metayer_ENG.pdf
      headings:
        about: ''
        interests: ''
        news: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
