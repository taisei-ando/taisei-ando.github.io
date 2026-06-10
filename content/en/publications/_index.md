---
title: Publications
cms_exclude: true
type: landing

design:
  spacing: '4rem'

sections:
  - block: collection
    content:
      title: Journal Articles
      filters:
        folders:
          - publications
        publication_type: 'article-journal'
      order: desc
    design:
      view: citation

  - block: collection
    content:
      title: Conference Proceedings Papers
      filters:
        folders:
          - publications
        publication_type: 'paper-conference'
      order: desc
    design:
      view: citation
---
