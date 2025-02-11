---
# Leave the homepage title empty to use the site title
title:
date: 2024-10-24
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Featured Publications 
      text: |-
        {{% callout note %}}
        **See Full Publication**  
        [**Google Scholar Link**](https://scholar.google.com/citations?user=wB9WetAAAAAJ&hl=en)
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: card
  - block: collection
    content:
      title: Recent Publications
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
        - name: CMLID
          tag: cmlid
        - name: CMSA
          tag: cmsa
        - name: CM Hate Speech
          tag: cm-hate
        - name: CMIR
          tag: cmir
        - name: Sarcasm Detection
          tag: sarcasm-detection
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    id: experience
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
        - title: Research Scholar (Ph.D.)
          company: Indian Institute of Technology (BHU), Varanasi
          company_url: 'https://www.iitbhu.ac.in/'
          company_logo: iitbhu
          location: Varanasi, India
          date_start: '2018-07-18'
          date_end: '2024-10-07'
          description: |2-
              Research projects include:

              * One
              * Two
              * Three
              
        - title: M.Tech Research Scholar
          company: University of Hyderabad
          company_url: 'https://uohyd.ac.in/'
          company_logo: uoh
          location: Hyderabad, India
          date_start: '2016-07-01'
          date_end: '2018-05-30'
          description: |2-
              Research projects include:

              * One
              * Two
              * Three
              
        - title: M.Sc project
          company: Pondicherry University
          company_url: 'https://www.pondiuni.edu.in/'
          company_logo: pu
          location: Puducherry, India
          date_start: '2014-08-01'
          date_end: '2016-06-30'
          description: |2-
              Research projects include:

              * One
              * Two
              * Three

    design:
      columns: '2'
  - block: accomplishments
    id: posts
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Recent News!'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: '2024-06-12'
          date_start: '2024-12-15'
          description: 'In collaboration with FIRE 2024, we are pleased to announce the call for participation for [CMIR-2024](https://cmir-iitbhu.github.io/cmir/), a shared task dedicated to information retrieval from code-mixed social media data.'
          organization: FIRE 2024
          organization_url: https://fire.irsi.org.in/fire/2025/home/
          title: CMIR-2024
          url: 'https://cmir-iitbhu.github.io/cmir/'
        #- certificate_url: 
        #  date_end: ''
        #  date_start: '2023-11-13'
        #  description: 'In collaboration with ACM SIGSPATIAL, we are pleased to announce the call for papers for [GeoSocial 2023](http://www.geosocial.iitkgp.ac.in/). The workshop aims to bring together a diverse community of researchers, practitioners, and students from various disciplines to exchange ideas, share knowledge, and foster collaboration in the burgeoning field of geocomputational and socio-economic data analysis.'
        #  organization: SigSpatial
        #  organization_url: https://sigspatial2023.sigspatial.org/
        #  title: GeoSocial 2023!
        #  url: 'http://www.geosocial.iitkgp.ac.in/'
        #- certificate_url: 
        #  date_end: ''
        #  date_start: '2023-10-22'
        #  description: 'In collaboration with CIKM 2023, we are pleased to announce the call for papers for [InfoWild 2023](https://wildinfo.ist.psu.edu/), a workshop dedicated to explore and enhance AI’s role in big data analysis for wildlife conservation, in brief, Nature Through the Lens of AI . It seeks to address crucial challenges related to data heterogeneity, scale integration, data privacy, mitigating biases, and decision-making under uncertainty. This workshop is centred around leveraging AI’s prowess in deciphering complex spatio-temporal data patterns for wildlife conservation, thereby contributing significantly to the broader canvas of AI for social good.'
        #  organization: CIKM
        #  organization_url: https://uobevents.eventsair.com/cikm2023/
        #  title: InfoWild 2023!
        #  url: 'https://wildinfo.ist.psu.edu/'
    design:
      columns: '2'

  
  
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  
  - block: features
    content:
      title: Skills
      items:
        - name: Natural lanuage processing
          #description: 100%
          icon: list-check
          icon_pack: fas
        - name: Social media data analytics
          #description: 10%
          icon: magnifying-glass-chart
          icon_pack: fas
        - name: Python, C, PyTorch
          #description: 10%
          icon: list-check
          icon_pack: fas
  
  - block: contact
    id: contact
    content:
      title: Contact
      #subtitle:
      #text: |-
      #Contact (add or remove contact options as necessary)
      email: suplife24@gmail.com
      phone: +919488205994
      #appointment_url: 'https://calendly.com'
      address:
        street: TF-01, Information Retrieval Lab, Dept. of Computer Science and Engineering, Indian Institute of Technology (Banaras Hindu University)
        city: Varanasi
        region: Uttar Pradesh
        postcode: '221005'
        country: India
        country_code: IND
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://x.com/SUPLIFE24'
        
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: ''
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      
    design:
      columns: '2'
---
