---
# Leave the homepage title empty to use the site title
title: ""
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography
    content:
      username: me
      text: ""
      button:
        text: En résumé (pdf)
        url: uploads/resume_fr.pdf
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
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
#  - block: resume-awards
 #   content:
  #    title: Awards
   #   username: me
---
