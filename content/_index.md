---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-08-19
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
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: animated-bg.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: "📚 My Current Research"
      subtitle: ""
      text: |-
        I am currently working at the Dynamic Medical Image and Computing (DMIC) Lab in the Biomedmial Engineering Department at UT Austin. I am (1) training a diffusion model to generate CT scans of lungs with fibrosis conditioned on lobe segmentation masks and (2) predicting lung exhale structure from inhale using VAE-compressed latent representations.
    design:
      columns: "1"
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
