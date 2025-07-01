---
# Leave the homepage title empty to use the site title
title:
date: 2025-07-01
type: landing


sections:
  - block: markdown
    content:
      title: 刘鸿课题组
      subtitle: ''
      text: 刘鸿博士多年来一直从事功能性高分子材料的理论设计与模拟工作，基于高分子反应动力学模型发展了粗粒化分子动力学耦合聚合反应的方法，可准确且高效地描述多种反应类型。进一步利用该方法研究并阐明了表面引发聚合反应中影响聚合物刷结构与性质的因素，明确了接枝聚合物材料的浸润性增强机理，解决了实验中聚合反应调控材料结构方面的多个重要问题。近年来在Science, ACS Macro Letters，Macromolecules，J. Chem. Phys.等学术期刊发表研究论文90余篇。<img src="2024_group_people_1.jpg" class="center-image" />

    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

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
      view: card
      columns: '1'
---
