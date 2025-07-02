---
# Leave the homepage title empty to use the site title
title:
date: 2025-07-02
type: landing

sections:
  - block: markdown
    content:
      title: 刘鸿课题组
      
      subtitle: ''
    design:
      background:
          image:
            filename: LhGroup.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: collection
    content:
      title: 论文发表
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 
    design:
      view: citation
      columns: '1'
---
