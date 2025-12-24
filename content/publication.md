---
title: Publications
cms_exclude: true
type: landing

view: citation


design:
  spacing: '5rem'

sections:
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
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
          - publication
        exclude_featured: false
    design:
      view: citation


# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---
