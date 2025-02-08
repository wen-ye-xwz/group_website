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
      logo:
        filename: logo.png
      text: |
        <br>
        
        The USC Melady Lab is a leader in advancing machine learning and data mining algorithms to extract meaningful insights from complex data. Our research spans a wide array of domains, including **time series modeling, interpretable machine learning, causal mining, deep learning for healthcare, social network analysis, physics-informed machine learning**. Through our innovative techniques, we have contributed to impactful discoveries and real-world applications across diverse disciplines. We collaborate with domain experts to apply developed methodologies across various fields such as computational biology, public health, and energy management. Our work aims to **provide practical solutions to pressing real world challenges**, shaping the future of intelligent systems and data-driven decision-making.

        JOIN US

        Prospective PhD students: If you are interested in working with us, please include Prof. Liu’s name in your application.

        Directed Research (DR) / Internship: If you are interested in directed research/internship opportunities, please fill out the application form. [Link](https://urldefense.proofpoint.com/v2/url?u=https-3A__goo.gl_forms_YYcMmdRevvymZiz42&d=DwMFaQ&c=clK7kQUTWtAVEOVIgvi0NU5BOUHhpN0H8p7CSfnc_gI&r=W6mNidmIFjjTIKxy6kS9pQ&m=cT0djUYyXGpkZXn8nBfboKiTLwKPWqJSe9l0eIH3Xww&s=6gPuAeUi8HZPpfLdm8yJqp_SbKCR7gjLbej0vKZyA_I&e=)
        
        Postdoc: If you are interested in postdoc positions, please fill out the application form. [Link](https://urldefense.proofpoint.com/v2/url?u=https-3A__goo.gl_forms_a07ewRJTqTb9WEVH3&d=DwMFaQ&c=clK7kQUTWtAVEOVIgvi0NU5BOUHhpN0H8p7CSfnc_gI&r=W6mNidmIFjjTIKxy6kS9pQ&m=cT0djUYyXGpkZXn8nBfboKiTLwKPWqJSe9l0eIH3Xww&s=uR62goEptf_5K1xaNXhMEj9d4P0LSzFg8CtOzQRTRhM&e=)



  
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
