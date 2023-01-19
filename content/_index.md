---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: samuel-scalzo-xyuYk9oLA8I-unsplash.jpg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '<br> Welcome 👋'
      subtitle: ''
      text: |-
        I'm an ongoing graduate student at the University of Edinburgh, majoring in Finance, Technology, and Policy (Fintech).

        My areas of interest include analytical skills, problem-solving, data-engineering and machine learning. I am detail-oriented and enjoy working with product and business teams to drive decisions using data. As my master's specialisation concentrates on FinTech, I have a vast appeal on blockchain and the financial market and am keen to utilise my analytical capabilities to tackle issues in financial sectors.

        Since 2014, I have been blending my analytical with programming skills. My last professional job was at Tokopedia (GoTo － Holding Company) as an Analytics Lead, supporting Payment and FinTech day-to-day decision-making in Tokopedia.

        **Specialties:** Analytics & Data, Leadership, Programming, Web3, Writing & Editing

        <br><br>

    design:
      columns: '1'
  - block: collection
    content:
      title: <br> Recent Posts <br> 
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
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
      view: showcase
      columns: '1'
---
