---
# Leave the homepage title empty to use the site title
title: ''
type: landing

design:
  # Default section spacing
  spacing: '2rem'

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: 
        <br/>
        As a specialist in veterinary preventive medicine with expertise in epidemiology and biostatistics, I focus on applying the <i>One Health</i> approach across various contexts — from animal population health to public health. Since 2025, I am a professor in veterinary livestock management at the Faculté de médecine vétérinaire, Université de Montréal (Rimouski campus), where I have the pleasure of teaching passionate students and leading exciting research projects.
        <br><br/>
      # Show a call-to-action button under your biography? (optional)
      button:
        text: In a nutshell (pdf)
        url: uploads/resume.pdf
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
        
      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
#  - block: resume-skills
 #   content:
  #    title: Skills & Hobbies
   #   username: me
#  - block: resume-awards
 #   content:
  #    title: Awards
   #   username: me
---