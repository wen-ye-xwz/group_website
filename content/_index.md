---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Melady Group USC
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **USC Melady Lab** is at the forefront of developing innovative machine learning and data mining algorithms to uncover insights from complex data. We have made significant advances in interpretable machine learning, temporal causal modeling, deep learning for healthcare, social network analysis, physics-informed machine learning, learning in games, autonomous vehicles, anomaly detection, climate science, and other areas. Our techniques have led to impactful discoveries and practical applications across many disciplines. We continue to push the boundaries of what’s possible with machine learning, striving to solve challenging real-world problems through novel algorithms and models that handle time series, spatial, relational, and other structured data types.
  
  - block: collection
    content:
      title: Latest News
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
      view: card
      columns: '1'
  

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
