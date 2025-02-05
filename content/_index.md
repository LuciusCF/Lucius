---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-02-04
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "test"
      # Show a call-to-action button under your biography? (optional)
      #button:
       # text: Get Started
       # url: blog/
    design:
      css_class: light
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: bg.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

---
