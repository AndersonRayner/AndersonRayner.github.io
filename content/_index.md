---
# Leave the homepage title empty to use the site title
title: 'matt'
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '2rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        Field roboticist, system architect, aero engineer, and low-level programmer who is always looking for the next challenging adventure.
        Whether the mission is deep underground or high in the air, I can duck tape, hot glue, and hack my way to success.

        Download my <a href="https://github.com/AndersonRayner/cv/releases/download/main/ANDERSON_Matt.pdf" class="btn btn-primary" target="_blank" rel="noopener">
        <i class="fas fa-download"></i> CV (Academic) </a> / <a href="https://raw.githubusercontent.com/AndersonRayner/cv/main/anderson_matt_cv_short.pdf" class="btn btn-primary" target="_blank" rel="noopener">
        <i class="fas fa-download"></i> CV (Industry) </a>
        
      headings:
        about: 'Summary'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true

      name:
        size: md # Options: xs, sm, md, lg (default), xl

      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: collection
    content:
      title: Projects
      text: 'Some example text for projects'
      filters:
        folders:
          - projects
        featured_only: false
      count: 3
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: papers
    content:
      title: Featured Publications
      text: Featured publications, all the cool ones
      filters:
        folders:
          - publications
        featured_only: true
      count: 3                     # show at most three items
    design:
      view: article-grid
      columns: 3

  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: false
      count: 6
    design:
      view: citation
      image_position: left

  # - block: collection
  #   content:
  #     title: Patents
  #     text: 'Patents'
  #     filters:
  #       folders:
  #         - patents
  #       featured_only: false
  #   design:
  #     view: article-grid
  #     columns: 2

---
