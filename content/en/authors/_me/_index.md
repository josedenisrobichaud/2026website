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
      text: "As a specialist in veterinary preventive medicine with expertise in epidemiology and biostatistics, I focus on applying the One Health approach across various contexts — from animal population health to public health. I’m currently a professor in veterinary livestock management at the Faculté de médecine vétérinaire, Université de Montréal (Rimouski campus), where I have the pleasure of teaching passionate students and leading exciting research projects."
      button:
        text: In a nutshell (pdf)
        url: /uploads/resume.pdf
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
        text_color_light: true
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
