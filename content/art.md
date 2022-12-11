---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20
title: Art
subtitle: blahblah

filters:
  folders:
   - /project
    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  tags:
    - art

  default_button_index: 0
  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  buttons:
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

In my spare time, I like to doodle and make some handcrafts. 