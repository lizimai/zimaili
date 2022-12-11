---
widget: portfolio # As of v5.8-dev, 'pages' is renamed 'collection'
headless: true  # This file represents a page section.

# Put Your Section Options Here (title, background, etc.) ...
title: Artwork
subtitle: ''

# Position of this section on the page
weight: 1

content:
  # Filter content to display
  filters:
    # The folders to display content from
    folders:
      - artwork
    tag: 'art'
  
  filter_default: 0
  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Watercolour
      tag: watercolour
    - name: Doodle
      tag: doodle
design:
  # Choose a listing view
  view: compact
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
---
