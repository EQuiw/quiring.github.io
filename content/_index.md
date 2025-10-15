---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-10-15
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'Selected Honors, Scholarships, and Awards'
      subtitle: ''
      text: |-
        - Best Paper Award at IEEE Deep Learning Security and Privacy Workshop (DLSP)
        - Dissertation Award, AI Talent of Lower Saxony, Germany, 2022
        - Distinguished Paper Award at USENIX Security Symposium 2022
        - Winner of the defender challenge at the Machine Learning Security Evasion Competition by Microsoft, 2020
        - Best Student Paper Award at IEEE International Workshop on Information Forensics and Security (WIFS), 2015
        - Scholarship by German Academic Exchange Service (DAAD), 2015
        - Deutschlandstipendium (Scholarship), sponsored by BASF SE, 2013-2015
        - Winner of Special Award of Münster’s Society for Applied Informatics for the best empirical thesis, 2013
        - Winner of Hays-AlumniUM-Bachelor-Award as the best BSc. student in graduating class, 2013
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Academic Activities'
      subtitle: ''
      text: |-
        **Membership in Program Committees / Conference Reviewing**:
        - 2019-2025 - IEEE Workshop on Deep Learning and Security (DLS)
        - 2023-2025 - Workshop on Robust Malware Analysis (WoRMA)
        - 2021-2024 - ACM Workshop on Artificial Intelligence and Security (AISec)
        - 2023 - IEEE European Symposium on Security and Privacy (EuroS&P)
        - 2022 - USENIX Security Artifact Evaluation Committee
        - 2022 - European Symposium on Research in Computer Security (ESORICS) Program Committee
        - 2021 - European Symposium on Research in Computer Security (ESORICS) Posters Program Committee
    
        **Journal Reviewing**:
        - IEEE Transactions on Information Forensics & Security (TIFS)
        - IEEE Intelligent Systems
        - Computer Science Review
        
        **Sub-Reviewing**:
        - IEEE Symposium on Security and Privacy (S\&P)
        - Network and Distributed System Security Symposium (NDSS)
        - ACM Conference on Computer and Communications Security (CCS)
        - USENIX Security Symposium
        - Annual Computer Security Applications Conference (ACSAC)
        - Symposium on Research in Attacks, Intrusions, and Defenses (RAID)
        - IEEE European Symposium on Security and Privacy (EuroS\&P)
        - ACM Asia Conference on Computer and Communications Security (ASIA CCS)
    design:
      columns: '1'
  #- block: collection
  #  id: publications
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publications
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    # Page type to display. E.g. post, talk, publication...
  #    page_type: blog
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #   filters:
  #      author: ''
  #      category: ''
  #      tag: ''
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ''
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: card
  #    # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
  
---
