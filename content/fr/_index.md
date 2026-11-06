---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        RALI
        
        Groupe de recherche
      image:
        filename: bienvenue.jpg
      text: |
        <br>
        
        Le laboratoire RALI (Recherche appliquée en linguistique informatique) est un groupe de recherche à l’Université de Montréal qui réunit des informaticiens et des linguistes se spécialisant dans le traitement automatique du langage naturel (TALN). Et toujours plus.
  
  - block: collection
    content:
      title: Dernières nouvelles
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
      page_type: event
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Dernières publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: '1'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Rencontrez l'équipe →" %}}
    design:
      columns: '1'
---
