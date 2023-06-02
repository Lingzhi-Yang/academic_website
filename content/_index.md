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
          company_url: 'https://mgv.pku.edu.cn/english/index.htm'
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

  - block: collection
    id: news
    content:
      title: News
      text: |-
        [I posted my latest work about **“CXCL12 as a Potential Marker for identifying AF Subset”** on AHA Scientific Sessions, virtual Poster Session 2022, and updated my work on **CIRCULATION** as an abstract.](https://www.ahajournals.org/doi/10.1161/circ.146.suppl_1.14674)
      filters:
        folders:
          - news
        exclude_featured: true
    design:
      columns: '2'
      view: list

  - block: collection
    id: featured
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        [Quickly filter recent publications](./publication/).
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
        National Scholarship for Master’s Degree Students. January 2022

        Meritorious student at Department Level January 2022

        Outstanding Individual in Scientific and Technological Innovation Chongqing Medical University. January 2022
        
        Outstanding Graduate of Chongqing Medical University. January 2020
        
        Second Prize in the ”Concept Cup” Experimental Competition. January 2019
        
        ”Excellent Award” at the Chongqing Medical University Undergraduate Basic Medical Science Innovation Forum and Experimental Design Competition. January 2018
        
        Second Prize at the University Level in the ”Foreign Language Teaching and Research Press (FLTPR)” National English Writing Competition January 2019
        
        Second Prize in Category C of the National English Contest for College Students. January 2019
        
        ”Outstanding Communist Youth League Member” of the Second Affiliated Hospital of Chongqing Medical University. January 2019
        
        Meritorious Student Scholarship at the Department Level, Chongqing Medical University. January 2020
        
        Meritorious Student Scholarship at the Department Level, Chongqing Medical University. January 2019
        
        Merit Student Scholarship at the University Level, Chongqing Medical University. January 2018
        
        Meritorious Student Scholarship at the Department Level, School of Chemistry and Chemical Engineering, Huazhong University of Science and Technology. January 2017
        
        Self-Improvement Scholarship of the School of Chemistry and Chemical Engineering, Huazhong University of Science and Technology. January 2017
        
        Excellent Academic Performance Scholarship of the School of Chemistry and Chemical Engineering, Huazhong University of Science and Technology. January 2017
      filters:
        folders:
          - Awards
        exclude_featured: true
    design:
      columns: '1'
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
