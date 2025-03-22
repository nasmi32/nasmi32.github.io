---
# Leave the homepage title empty to use the site title
title:
date: 2025-03-22
type: landing

sections:
  - block: hero
    content:
      title: |
        Неравновесная агрегация, фракталы
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Состав исследовательской группы: Ищенко И. О., Мишина А. А., Дикач А. О., Барсегян В. Л., Галацан Н. И., Дудырев Г. А.
          
  - block: collection
    content:
      title: Последние новости
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
      title: Последние работы
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: ''
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
