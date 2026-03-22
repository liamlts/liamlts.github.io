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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
        shape: circle
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
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks & Presentations
      filters:
        folders:
          - events
    design:
      view: card
---
