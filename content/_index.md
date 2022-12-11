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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I am happy to connect with people to talk about science and arts. Write me a message!
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
