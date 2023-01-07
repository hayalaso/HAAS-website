---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  #design:
  #  background: 
  #    gradient_angle: 180
  #    gradient_start: '#4bb4e3'
  #    gradient_end: '#2b94c3'
  id: about
- block: features
  content:
    items:
    - description: 100%
      icon: code
      icon_pack: "fas"
      name: C++
    - description: 100%
      icon: python
      icon_pack: fab
      name: Python
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 90%
      icon: github
      icon_pack: fab
      name: Git
    - description: 100%
      icon: overleaf
      icon_pack: ai
      name: Overleaf/Latex
    title: Skills
  link: /#skills
  id: skills
- block: experience
  content:
    date_format: Jan 2022
    items:
    - company: The Pennsylvania State University
      company_logo: ""
      company_url: "www.psu.edu"
      date_end: ""
      date_start: "2022-01-04"
      description: |2-
          Member of HAWC, IceCube and AMON
          Responsibilities include:

          * Software development and maintance
          * Data Analysis
          * Monitoring or realtime alerts
          * Science coordinator of HAWC
          * Multiwavelength and Multimessenger coordinator in HAWC
      location: Pennsylania
      title: Assistant Research Professor
    - company: The Pennsylvania State University
      company_logo: ""
      company_url: ""
      date_end: "2021-01-03"
      date_start: "2017-05-14"
      description: Member of HAWC, IceCube and AMON.
      location: Pennsylvania
      title: Postdoctoral Scholar
    - company: Michigan Technological University
      title: PhD Thesis Research
      date_start: 2011-09-01
      date_end: 2017-04-30
      description: |2- 
          HAWC Researcher
          Responsabilities:
          
          * Calibration hardware and software
          * Algorithm to reconstruct events
          * Study of gamma-ray emission from the Fermi Bubbles
    - company: Instituto Tecnológico y de Estudios Superiores de Monterrey
      location: Monterrey, N.L., México
      date_start: "2011-01-01"
      date_end: "2011-07-30"
      description: Work on Maxwell's equations focusing on polarization of light in birefrigence media.
      title: Research Intern at ITESM-Photonics and Mathematical Optics Group
    - company: Michigan Technological University
      title: Summer Research Intern
      date_start: 2010-05-01
      date_end: 2010-08-01
    title: Experience
  design:
    columns: "2"
  link: /#experience
  id: experience
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - title: Swift Cycle 1r65 Guest Investigator Program
      organiztion: NASA
      date_start: 2020-04-15
      description: "Proposal with title *Swift Follow-up Searches of Coincidences from the Neutrino + Gamma-Ray Program*"

    - title: Swift Cycle 15 Guest Investigator Program
      organiztion: NASA
      date_start: 2019-04-15
      description: "Proposal with title *Swift Follow-up Searches of low false-alarm rate high-energy neutrino and gamma-ray coincidences*"

    - #certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2018-10-01"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""

    - title: Henes Fellowship Assistant Award
      organization: Michigan Technological University
      date_start: 2017-01-01
      date_end: 2017-04-30

    - title: Doctoral Finishing Fellowship Award
      organization: Michigan Technological University
      date_start: 2016-09-01
      date_end: 2016-12-10

    - title: Outstanding Teaching Assistant Award
      organization: Michigan Technological University
      date_start: 2012-05-01

    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
  url: /#accomplishments
  id: accomplishments

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: AMON
      tag: AMON
    - name: HAWC
      tag: HAWC
    - name: SWGO
      tag: SWGO
    default_button_index: 0
    filters:
      folders:
      - project
    title: Research
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects

#- block: markdown
#  content:
#    subtitle: ""
#    text: '{{< gallery album="demo" >}}'
#    title: Gallery
#  design:
#    columns: "1"
#- block: collection
#  content:
#    filters:
#      featured_only: true
#      folders:
#      - publication
#    title: Publications
#  design:
#    columns: "2"
#    view: card
#  id: featured
- block: collection
  content:
    filters:
      exclude_featured: false
      #category: "2"
      folders:
      - publication
    #text: |-
    #  {{% callout note %}}
    #  Quickly discover relevant content by [filtering publications](./publication/).
    #  {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
  id: featured

#- block: collection
#  content:
#    filters:
#      folders:
#      - event
#    title: Recent & Upcoming Talks
#  design:
#    columns: "2"
#    view: compact
#  id: talks

#- block: tag_cloud
#  content:
#    title: Popular Topics
#  design:
#    columns: "2"
- block: contact
  content:
    address:
      city: University Park
      country: United States
      country_code: US
      postcode: "16802"
      region: PA
      street: Davey Lab B19
    
    autolink: true
    directions: Office 206A Osmond on second Floor 
    email: hgayala@psu.edu
    #form:
    #  formspree:
    #    id: null
    #  netlify:
    #    captcha: false
    #  provider: netlify
    office_hours:
    #- Monday 10:00 to 13:00
    #- Wednesday 09:00 to 10:00
    phone:  
    subtitle: null
    #text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    #  ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
