---
# Leave the homepage title empty to use the site title
title: ''
type: landing

design:
  # Default section spacing
  spacing: '2rem'

sections:
  - block: markdown
    content: 
      text: |
        *Bienvenue sur mon site!*
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
        text_color_light: true 
      spacing:
        padding: ["10px", "0", "30px", "0"]
  - block: hero
    content:
      title: 'Programme de recherche'
      text: |
        Notre objectif est d'explorer l'intersection des enjeux technologiques, sociétaux, environnementaux et climatiques entourant la production laitière afin de soutenir sa durabilité et sa résilience. En nous appuyant sur des bases épidémiologiques, nous développons des connaissances et des outils liés aux innovations technologiques, aux pratiques de gestion et aux collaborations interdisciplinaires pour optimiser la santé des animaux, des producteurs, des consommateurs et de l'environnement.
      primary_action: 
        text: Rencontrez l'équipe
        url: team/
        icon: sparkles
      secondary_action:
        text: Découvrez nos projets
        url: projects/
      announcement:
        text: Nous sommes au campus de Rimouski de l'Université de Montréal.
        link:
          text: En savoir plus
          url: news/
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
        text_color_light: true
      spacing:
      # Top, Right, Bottom, Left
        padding: ["10px", "0", "10px", "0"]
      
  - block: research-areas
    content:
      title: 'Sujets de recherche'
      items:
        - name: Santé des vaches laitières
          description: Exploration des performances, des conditions, des méthodes diagnostiques et des traitements pour les vaches laitières
          image: projects/cow.jpg
          status: actif
          topics:
            - Reproduction
            - Diagnostique
            - Traitement
          #team_size: 2
          #publications: 0
          #funding: MAPAQ
          #cta:
           # text: Learn More
            #url: /research/computational-biology

        - name: Technologies
          description: Évaluation de l'adoption des technologies et développement de solutions de gestion basées sur l'IA pour les exploitations laitières
          image: projects/techno.jpg
          status: développement
          topics:
            - Développement
            - Impact
            - Apprentissage machine
          #team_size: 
          #publications: 32 papers
          #funding: Fondation AGRIA

        - name: Une Seule Santé
          description: Amélioration des diagnostics, la gestion responsable des antimicrobiens et le bien-être des producteurs en production laitière
          image: projects/one-health.jpg
          status: planification
          topics:
            - Suivi
            - Qualité de vie
            - Collaboration
          #team_size: 6 
          #publications: 28 papers
          #funding: 
    design:
      layout: cards 
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.5
          size: cover
          position: center
        text_color_light: true 
      design:
        spacing:
        # Top, Right, Bottom, Left
          padding: ["0px", "0", "0px", "0"]
  - block: contact-info
    id: contact
    content: 
      title: Contact
      visit_title: En personne
      connect_title: En ligne
      #map_url: https://www.google.com/maps/place/University+of+Quebec+at+Rimouski/@48.4525478,-68.5121012,17z/data=!3m1!4b1!4m6!3m5!1s0x4c95d9bf34e2acab:0x9a4c836523397f8e!8m2!3d48.4525478!4d-68.5121012!16zL20vMDN6cjho?authuser=0&hl=en&entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D
      address:
        lines:
          - José Denis-Robichaud
          - Université de Montréal
          - 300, allée des Ursulines
          - Bureau T-330
          - Rimouski (QC) G5L 3A1
          - Canada
      email: jose.denis-robichaud@umontreal.ca
      #social:
       # - icon: brands/linkedin
        #  url: https://www.linkedin.com/in/jose-denis-robichaud
        #- icon: academicons/google-scholar
         # url: https://scholar.google.com/citations?user=I-jVqu8AAAAJ&hl=en
        #- icon: academicons/orcid
         # url: https://orcid.org/0000-0002-7742-0631
        #- icon: brands/instagram
         # url: https://www.instagram.com/nomadinthewind
        #- icon: brands/github
         # url: https://github.com/josedenisrobichaud
        #- icon: academicons/dataverse
         # url: https://dataverse.harvard.edu/dataverse/josedr
      prospective:
        title: Futurs étudiant·es
        text: Vous souhaitez rejoindre notre groupe? Nous recherchons des étudiant·es curieux·ses et motivé·es.
        button:
          text: Voir les opportunités
          url: /projects
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      spacing:
      # Top, Right, Bottom, Left
        padding: ["10px", "0", "10px", "0"]
  

---
