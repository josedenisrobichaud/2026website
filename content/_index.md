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
      title: 'Welcome to the DR² research group'
    design:
      justify: center
      spacing:
      # Top, Right, Bottom, Left
        padding: ["20px", "0", "0px", "0"]
  - block: hero
    content:
      title: 'Research program'
      text: |
        Our goal is to explore the intersection of technological, societal, environmental and climatic issues surrounding dairy production in order to support its sustainability and resilience. Building on epidemiological foundations, we are developing knowledge and tools related to technological innovations, management practices, and interdisciplinary collaborations to optimize the health of animals, producers, consumers and the environment.
      primary_action: 
        text: Meet the team
        url: /#team
        icon: sparkles
      secondary_action:
        text: Discover our projects
        url: projects/
      announcement:
        text: We are at the Rimouski campus of the Université de Montréal. 
        link:
          text: Read more
          url: /#news
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
      spacing:
      # Top, Right, Bottom, Left
        padding: ["0px", "0", "10px", "0"]
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
            - Metabolic diseases
          #team_size: 3
          #publications: 45 
          #funding: $2.5M
          #cta:
           # text: Learn More
            #url: /research/computational-biology

        - name: Technologies
          description: Investigating technology adoption effects on dairy operations and developing AI-based management solutions
          image: projects/techno.jpg
          status: emerging
          topics:
            - Development
            - Impact
            - Utilization 
            - Machine learning
          #team_size: 8 researchers
          #publications: 32 papers
          #funding: $1.8M

        - name: One Health
          description: Advancing One Health in dairy systems through improved diagnostics, antimicrobial stewardship, and farmer wellbeing
          image: projects/one-health.jpg
          status: planning
          topics:
            - Monitoring
            - Quality of life
            - Collaboration
          #team_size: 6 researchers
          #publications: 28 papers
          #funding: $1.2M
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
      design:
        spacing:
        # Top, Right, Bottom, Left
          padding: ["0px", "0", "0px", "0"]
  - block: contact-info
    id: contact
    content: 
      title: Contact us
      visit_tile: 'Where we are'
      connect_tile: 'Connect with us'
      map_url: https://www.google.com/maps/place/University+of+Quebec+at+Rimouski/@48.4525478,-68.5121012,17z/data=!3m1!4b1!4m6!3m5!1s0x4c95d9bf34e2acab:0x9a4c836523397f8e!8m2!3d48.4525478!4d-68.5121012!16zL20vMDN6cjho?authuser=0&hl=en&entry=ttu&g_ep=EgoyMDI1MTIwOS4wIKXMDSoASAFQAw%3D%3D
      address:
        lines:
          - José Denis-Robichaud
          - Département de biomédecine vétérinaire
          - Université de Montréal
          - 300, allée des Ursulines
          - Rimouski (QC) G5L 3A1
          - Canada
      email: jose.denis-robichaud@umontreal.ca
      show_from: true
      social:
        - icon: brands/linkedin
          url: https://www.linkedin.com/in/jose-denis-robichaud
        - icon: academicons/google-scholar
          url: https://scholar.google.com/citations?user=I-jVqu8AAAAJ&hl=en
        - icon: academicons/orcid
          url: https://orcid.org/0000-0002-7742-0631
        - icon: brands/instagram
          url: https://www.instagram.com/nomadinthewind
        - icon: brands/github
          url: https://github.com/josedenisrobichaud
        - icon: academicons/dataverse
          url: https://dataverse.harvard.edu/dataverse/josedr
      prospective:
        title: Prospective students
        text: Interested in joining our lab? We're looking for curious and motivated students.
        button:
          text: View opportunities
          url: /opportunities
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      spacing:
      # Top, Right, Bottom, Left
        padding: ["10px", "0", "10px", "0"]
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
