---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R
          # description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          # description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Multi-omics data analysis
          # description: 100%
          icon: react
          icon_pack: fab
        # - name: Photography
        #   description: 10%
        #   icon: camera-retro
        #   icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: M.M. in Clinical Medicinee
          company: ChongQing Medical University(CQMU)
          company_url: 'https://www.cqmu.edu.cn/'
          company_logo: CQMU
          location: Chongqing, China
          date_start: '2021-09-01'
          date_end: '2024-07-01'
          description: |2-
              In 1st affiliated hospital of Chongqing medical university, I worked for:

              * Standardized training for resident physicians
              * Clinical investigation
              * Bioinformatic research

        - title: BMed in Clinical Medicine
          company: ChongQing Medical University(CQMU)
          company_url: 'https://www.cqmu.edu.cn/'
          company_logo: CQMU
          location: Chongqing, China
          date_start: '2017-09-01'
          date_end: '2021-09-01'
          description: |2-
              Specialization: fulltime medical training
              
        - title: Neurological and Cognitive Sciences Summer School
          company: PKU-IDG/McGovern Institute For Brain Research
          company_url: 'https://www.cqmu.edu.cn/'
          company_logo: PKU
          location: Beijing, China
          date_start: '2018-09-01'
          date_end: '2018-10-01'
          description: |2-
              Neurological and Cognitive Sciences Summer School

        - title: Joint Training Program in Clinical Medicine
          company: Huazhong University of Science and Technology(HUST)
          company_url: 'https://www.hust.edu.cn/'
          company_logo: HUST
          location: Wuhan, China
          date_start: '2016-09-01'
          date_end: '2017-09-01'
          description: |2-
          Specialization: joint training program for foundational subjects.
    design:
      columns: '2'

  - block: experience
    id: news
    content:
      title: News
      
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      * Standardized training for resident physicians
      * Standardized training for resident physicians
      * Standardized training for resident physicians
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

  - block: collection
    id: featured
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        # - name: Deep Learning
        #   tag: Deep Learning
        # - name: Other
        #   tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: Awards
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - Awards
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
    # id: featured
    # content:
    #   title: Featured Publications
    #   filters:
    #     folders:
    #       - publication
    #     featured_only: true
    # design:
    #   columns: '2'
    #   view: card
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: lingzhi_yang@outlook.com
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
