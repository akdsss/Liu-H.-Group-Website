---
# Leave the homepage title empty to use the site title
title:
date: 2025-07-02
type: landing


sections:
  - block: markdown
    content:
      title: Prof. Liu's Group
      subtitle: ''
      text: <img src="group_photo.jpg" class="center-image" />

    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: collection
    content:
      title: NEWS
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
  


  - block: collection
    content:
      title: PUBLICATIONS
      text: ""
      count: 2
      filters:
        folders:
          - publication
        publication_type: 
    design:
      view: card
      columns: '1'
---
