---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  # spacing: "6rem"
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: CV (Academic)
      #   url: https://raw.githubusercontent.com/AndersonRayner/cv/main/anderson_matt_cv_short.pdf

    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          # filename: flat-mountains.svg
          # filename: subtle-prism.svg
          # filename: topography.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true

  # - block: features
  #   content:
  #     title: Skills
  #     # subtitle: Section subtitle
  #     # text: Section text
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  #     design:
  #       columns: 3

  - block: skills
    # content:
    #   title: Skills and Experience
    design:
      # width: full
    #   view: article-grid
      columns: 2

  - block: collection
    id: projects
    content:
      title: Projects
      count: 6
      filters:
        folders:
          - project
        featured_only: false
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: papers
    content:
      title: Publications
      count: 6
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 3

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]

  # - block: cta-button-list
  #   content:
  #     # Need a custom icon?
  #     # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
  #     buttons:
  #       - text: Read my latest paper on LLMs
  #         icon: academicons/arxiv
  #         url: https://arxiv.org/abs/2304.01852
  #       - text: Watch my new YouTube video to achieve 20x productivity
  #         icon: brands/youtube
  #         url: https://youtube.com
  #       - text: Connect with me on LinkedIn
  #         icon: brands/linkedin
  #         url: https://linkedin.com

---
