---
widget: portfolio
# This file represents a page section.
headless: true
# Order that this section appears on the page.
weight: 30
title: Artworks done during freetime
subtitle: ''
content:
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
    # Uncomment below to only show content with specific tags:
#    tags:
#      - Machine Learning
    # Uncomment below to exclude content with specific tags:
#    exclude_tags:
#      - preface    
    # Uncomment below to show specific Hugo Page kinds
    #kinds:
    #  - page
#      - section

  # Field to sort by, such as Date or Title
#  sort_by: 'Date'
#  sort_ascending: false

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Watercolour
      tag: watercolour
    - name: Doodle
        tag: doodle     
design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---