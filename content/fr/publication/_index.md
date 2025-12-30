---
title: Publications
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: collection
    id: papers
    content:
      title: En vedette
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      fill_image: false
      columns: 2
  - block: collection
    content:
      title: Publications récentes
      filters:
        folders:
          - publication_all
        exclude_featured: true
    design:
      view: citation

share: FALSE

---
