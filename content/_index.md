---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: ""  # Leave empty if no text is needed
      text: ""  # Optional subtitle
      alignment: center
    design:
      background:
        color: "#ffffff"
        image:
          filename: mountains.JPG  # Replace with your banner image in `assets/media/`
          size: cover
          position: center
          filters:
            brightness: 1.0
        height: "30vh"  # Adjust height for a narrower banner
        parallax: false
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download my CV
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
---
