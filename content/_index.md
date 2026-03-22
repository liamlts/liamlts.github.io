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
          enable: true
      name:
        size: lg
      avatar:
        size: large
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research centers on quantum materials characterization using synchrotron-based X-ray spectroscopies. I investigate altermagnetism, van der Waals magnets, frustrated magnetic systems, and magnetocaloric materials at major international facilities including ESRF, Diamond Light Source, SOLEIL, MAX IV, and NSLS-II.

        As Principal Investigator, I manage over $1M in beamtime allocations across 15+ experimental campaigns. I also pursue a JD at Hofstra Law School focused on energy and environmental policy, where I serve as President of the Energy & Environmental Law Society.
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
