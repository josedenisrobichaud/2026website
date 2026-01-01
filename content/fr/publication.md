---
title: Publications
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: collection
    content:
      title: En vedette
      filters:
        folders:
          - publications
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
          - publications
        exclude_featured: false
    design:
      view: citation

share: FALSE

---
