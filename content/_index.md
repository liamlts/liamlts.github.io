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
      subtitle: 'Lead proposer on successful beamtime proposals across DOE national and international user facilities'
      text: |-
        **DOE National User Facilities**
        NSLS-II, Brookhaven National Laboratory (2-ID, SIX) · Advanced Photon Source, Argonne National Laboratory (Sector 27) · Advanced Light Source, Lawrence Berkeley National Laboratory (4.0.2)

        **International Synchrotrons**
        ESRF, France (ID32) · Diamond Light Source, UK (I21, I10) · SOLEIL, France (DEIMOS, SEXTANTS) · MAX IV, Sweden (VERITAS) · CHESS, Cornell (PIPOXS, QM2) · Canadian Light Source (BXDS)

        **Free-Electron Laser & THz Facilities**
        TELBE, Helmholtz-Zentrum Dresden-Rossendorf · TeraFERMI, Elettra Sincrotrone Trieste
    design:
      columns: '1'
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
