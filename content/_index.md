---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
    design:
      background:
        color: black
        text_color_light: false
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.7
          size: cover
          position: left
          parallax: true    
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
    # A section created with the Portfolio widget.
    # This section displays content from `content/project/`.
    # See https://wowchemy.com/docs/widget/portfolio/
  - block: portfolio
    id: projects
    content:
      title: 'Projects'
      filters:
        folders:
          - project
          - art
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Science
          tag: science
        - name: Art
          tag: art
    design:
      columns: '1'
      view: masonry
      flip_alt_rows: true
      background: {}
      spacing: {padding: [0, 0, 0, 0]}
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        **[See more of my artwork]({{< relref "../art" >}})**

        {{< gallery album="gallery">}}
    design:
      columns: '1'
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 60%
          icon: r-project
          icon_pack: fab
        - name: linux
          description: 50%
          icon: linux
          icon_pack: fab
        - name: github
          description: 100%
          icon: github
          icon_pack: fab                      
        - name: Statistics
          description: 60%
          icon: chart-line
          icon_pack: fas
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I am happy to connect with people to talk about science and art. Write me a message!
      # Contact (add or remove contact options as necessary)
      email: zimai.li@evobio.eu
      address:
        street: Hans-Knöll-Straße 8
        city: Jena
        region: Thuringia
        postcode: '07745'
        country: Germany
        country_code: DE
    design:
      columns: '2'
---
