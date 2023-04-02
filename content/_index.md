---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: v1/about #about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: 
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: R Programming
          description: Data Analysis, Statistics, ETL, <br> Graphics, Machine Learning
          icon: r-project
          icon_pack: fab
        - name: Python Programming
          description: Data Analysis, ETL, Graphics, <br> Machine Learning, Deep Learning
          icon: python
          icon_pack: fab
        - name: Databases
          description: Oracle, MySQL, SQLite, SQL Server <br> SQL and PL/SQL language
          icon: database
          icon_pack: fas 
        - name: Reproducible Research
          description: R Markdown, Jupyter Notebook, STATA scripts
          icon: markdown
          icon_pack: fab 
        - name: Artificial Intelligence
          description: Machine Learning and Deep Learning (Supervised/Unsupervised)
          icon: laptop-code
          icon_pack: fas    
        - name: Biostatistics
          description: Regression, Survival analysis, <br> Parametric/Non-Parametric tests
          icon: chart-line
          icon_pack: fas
        - name: eCRF
          description: Development of web apps with <br> Oracle APEX and REDCap
          icon: table-list
          icon_pack: fas
        - name: Interactive Dashboards
          description: Extracting insights from data <br> with QlikView and Plotly
          icon: chart-pie
          icon_pack: fas
        - name: Graphics
          description: Photoshop, GIMP
          icon: image
          icon_pack: fas
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
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content: 
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle: 
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/RE2TT9G85YSF
          date_end: '2021-11-30'
          date_start: '2021-10-01'
          description: >
            Courses Included:
              - AI for Medical Diagnosis ([Certificate](https://www.coursera.org/account/accomplishments/certificate/3LNY8CDLFLKE))
              - AI for Medical Treatment ([Certificate](https://www.coursera.org/account/accomplishments/certificate/RT4VUX5FKK4Q))
              - AI for Medical Prognosis ([Certificate](https://www.coursera.org/account/accomplishments/certificate/H3Y6Y8YVA3B9))

          organization: Coursera
          organization_url: https://www.coursera.org
          title: AI for Medicine Specialization
          url: 
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/4T6RBYUUDB5Z
          date_end: '2022-12-31'
          date_start: '2022-10-01'
          description: 
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Network and Deep Learning
          url:   
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/6KD2E2SQENYG
          date_end: '2022-12-31'
          date_start: '2022-10-02'
          description: 
          organization: Coursera
          organization_url: https://www.coursera.org
          title: > 
            Improving Deep Neural Networks: <br> Hyperparameter tuning, Regularization and Optimization
          url:
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/8WBY94PNSH4R
          date_end: '2022-12-31'
          date_start: '2022-10-03'
          description: 
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Structuring Machine Learning Projects
          url:
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/39T7YV868JBA
          date_end: '2022-12-31'
          date_start: '2022-10-04'
          description: 
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Convolutional Neural Networks
          url: 
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/3MJ6NZKLFBPP
          date_end: '2022-12-31'
          date_start: '2022-10-05'
          description: 
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Sequence Models
          url:  
        - certificate_url: 
          date_end: ''
          date_start: '2009-09-01'
          description: 
          organization: AICA (Associazione Italiana per l'Informatica e il Calcolo Automatico)
          organization_url: https://www.aicanet.it/
          title: ECDL Health
          url:     
    design:
      columns: '2'
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: compact
  #    columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
  #    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
  #    # Filter toolbar (optional).
  #    # Add or remove as many filters (`filter_button` instances) as you like.
  #    # To show all items, set `tag` to "*".
  #    # To filter by a specific tag, set `tag` to an existing tag name.
  #    # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
  #    # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  - block: collection
    id: publications
    content:
      title: Recent Publications
      #text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: #test@example.org
      phone: #888 888 88 88
      appointment_url: #'https://calendly.com'
      address:
        street: #450 Serra Mall
        city: #Stanford
        region: #CA
        postcode: #'94305'
        country: #United States
        country_code: #US
      directions: #Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        #- 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      contact_links:
        #- icon: twitter
        #  icon_pack: fab
        #  name: Twitter Me
        #  link: 'https://twitter.com/Twitter'
        - icon: telegram
          icon_pack: fab
          name: Telegram Me
          link: 'https://telegram.me/MatteoValerio'  
        #- icon: skype
        #  icon_pack: fab
        #  name: Skype Me
        #  link: 'skype:echo123?call'
        #- icon: video
        #  icon_pack: fas
        #  name: Zoom Me
        #  link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
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
