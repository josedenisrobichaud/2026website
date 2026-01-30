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
      username: _me
      text: "<br>Spécialiste en médecine vétérinaire préventive, avec une expertise en épidémiologie et en biostatistique, je m’intéresse à l’application concrète de l’approche Une Seule Santé — de la santé des populations animales à celle des humains. Je suis professeure en gestion des élevages à la Faculté de médecine vétérinaire de l’Université de Montréal (campus de Rimouski), où j’ai le plaisir d’enseigner à des étudiant·es engagé·es et de mener des projets de recherche passionnants.<br><br>"
      button:
        text: En résumé (pdf)
        url: /uploads/resume_fr.pdf
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
      username: _me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
#  - block: resume-awards
 #   content:
  #    title: Awards
   #   username: _me
---
