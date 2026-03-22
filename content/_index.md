---
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: lg
      avatar:
        size: large
        shape: rounded
  - block: collection
    id: projects
    content:
      title: Research
      subtitle: ''
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
  - block: markdown
    id: facilities
    content:
      title: 'Synchrotron & Facility Experience'
      subtitle: ''
      text: |-
        {{< synchrotron-map >}}
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      subtitle: 'Peer-reviewed & Conference Proceedings'
      filters:
        folders:
          - publications
    design:
      view: card
  - block: collection
    id: talks
    content:
      title: Talks & Presentations
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: card
---
