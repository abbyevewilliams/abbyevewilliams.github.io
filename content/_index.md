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
        text: Click here to download my CV
        url: uploads/cv_feb25.pdf
    design:
      css_class: light
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          #filename: mountains.JPG
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
      content:
        background_color: rgba(255, 255, 255, 0.7)  # Semi-transparent white behind text
---
