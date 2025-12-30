---
title: News
type: landing 

design:
  # Default section spacing
  spacing: '5rem'


sections:
  - block: collection
    content:
      title: News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: news 
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
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
      
      
share: FALSE
---
