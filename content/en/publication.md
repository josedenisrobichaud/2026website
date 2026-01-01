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
      title: Featured Publications
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
      title: Recent Publications
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      view: citation

share: FALSE

---
