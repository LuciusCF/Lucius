---
# Leave the homepage title empty to use the site title
title: "Home"
date: 2025-02-04
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '3rem', 0]
---
