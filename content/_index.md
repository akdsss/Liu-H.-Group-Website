---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 朱有亮课题组
      subtitle: ''
      image: 2024_group_people_0.jpg
      text:
      吉林大学朱有亮课题组专注于高分子/超分子的大尺度分子动力学模拟方法和软件、高分子材料力学性能的分子机理、共价有机框架的生长动力学等领域的研究。自主研发了分子动力学模拟软件GALAMOST 和 PYGAMD 并取得了一系列重要应用，软件应用成果已经在science等国际著名期刊发表论文超过200篇。
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen      
  
  - block: collection
    content:
      title: 组内新闻
      subtitle:
      text:
      count: 5
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
      title: 最新发表
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
