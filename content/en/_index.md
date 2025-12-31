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
        *Welcome to my website!*
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
      title: 'Research Program'
      text: |
        Our goal is to explore the intersection of technological, societal, environmental and climatic issues surrounding dairy production in order to support its sustainability and resilience. Building on epidemiological foundations, we are developing knowledge and tools related to technological innovations, management practices, and interdisciplinary collaborations to optimize the health of animals, producers, consumers and the environment.
      primary_action: 
        text: Meet the team
        url: team/
        icon: sparkles
      secondary_action:
        text: Discover our projects
        url: projects/
      announcement:
        text: We are at the Rimouski campus of the Université de Montréal. 
        link:
          text: Read more
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
      title: 'Research Areas'
      items:
        - name: Dairy cow health
          description: Investigating reproductive performance, disorders, diagnostic methods, and therapeutic interventions in dairy cows
          image: projects/cow.jpg
          status: active
          topics:
            - Reproduction
            - Diagnostic
            - Treatment
          #team_size: 2
          #publications: 0
          #funding: MAPAQ
          #cta:
           # text: Learn More
            #url: /research/computational-biology

        - name: Technologies
          description: Assessing technology adoption effects on dairy operations and developing AI-based management solutions
          image: projects/techno.jpg
          status: emerging
          topics:
            - Development
            - Impact
            - Machine learning
          #team_size: 
          #publications: 32 papers
          #funding: Fondation AGRIA

        - name: One Health
          description: Advancing One Health in dairy systems through improved diagnostics, antimicrobial stewardship, and farmer wellbeing
          image: projects/one-health.jpg
          status: planning
          topics:
            - Monitoring
            - Quality of life
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
            brightness: 1.0
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
      visit_title: Visit
      #map_url: https://www.google.com/maps/place/University+of+Quebec+at+Rimouski/@48.4525478,-68.5121012,17z/data=!3m1!4b1!4m6!3m5!1s0x4c95d9bf34e2acab:0x9a4c836523397f8e!8m2!3d48.4525478!4d-68.5121012!16zL20vMDN6cjho?authuser=0&hl=en&entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D
      address:
        lines:
          - José Denis-Robichaud
          - Département de biomédecine vétérinaire
          - Université de Montréal
          - 300, allée des Ursulines
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
        title: Prospective students
        text: Interested in joining our group? We're looking for curious and motivated students.
        button:
          text: View opportunities
          url: /en/projects
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      spacing:
      # Top, Right, Bottom, Left
        padding: ["10px", "0", "10px", "0"]
  

---
