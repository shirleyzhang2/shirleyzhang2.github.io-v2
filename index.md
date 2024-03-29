---
layout: home
header:
  title: Hi, I'm Shirley!
  text: >
    Welcome to my website&#128515;
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: About Me
    text: I'm a 4th year Civil Engineering Student at the University of Toronto passionate about the interface between infrastructure and technology.
    actions:
      - title: More about me
        #url: '#page-top'
        url: 'about'
        class: btn-light


  - type: services.html
    section_id: services
    #background_style: bg-info
    title: My Interests
    services:
      - title: Critical Infrastructure
        text: 
        icon: fa-gem
        #url: https://startbootstrap.com/
      - title: System resilience
        text: 
        icon: fa-paper-plane
      - title: Programming
        text: 
        icon: fa-laptop-code
      - title: Cooking
        text: 
        icon: fa-heart
      # - title: Other 1
      #   text: Some not-so long text here.
      #   icon: fa-heart
      # - title: Other 2
      #   text: Some not-so long text here.
      #   icon: fa-heart

  - type: aside.html
    section_id: aside
    title: Recent Projects
    actions:
      - title: Learn more
        url: 'projects'
        class: btn-light
  
  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Terrestrial Energy Inc.
        text: Nuclear containment design against aircraft & seismic loading
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: aia.png
        url: 'project'
      - title: Arup
        text: Crowd-induced floor vibration mitigation
        icon: buckeyethon.jpg
        url: 'project'
      - title: Rocscience Inc.
        text: Geotechnical software development
        icon: settle3.PNG
        url: 'project'
      - title: U of T Seismic Design Team
        text: In-house design & analysis script for seismic-proof high rises
        icon: ab_main.png
        url: 'project'
      - title: U of T Concrete Canoe Team
        text: In-house hull design script for concrete canoes
        icon: CAP.PNG
        url: 'project'
      - title: U of T Centre for Resilience of Critical Infrastructure
        text: Safeguarding Liquefied Natural Gas Storage
        icon: lng.jpg
        url: 'project'

  # - type: members.html
  #   section_id: members
  #   title: Our Crew!
  #   background_style: bg-info text-white
  #   members:
  #     - title: Christina M. Aponte
  #       text: Singer and Songwriter
  #       image: assets/img/members/person1.jpg
  #       url: '#'
  #     - title: Gary D. Stevens
  #       text: Bass guitar.
  #       image: assets/img/members/person2.jpg
  #       url: '#'
  #     - title: Devon J. Fletcher
  #       text: Lead guitar.
  #       image: assets/img/members/person3.jpg
  #       url: '#'
  #     - title: Todd E. Anderson
  #       text: Drums, percussion.
  #       image: assets/img/members/person5.jpg
  #       url: '#'
  #     - title: Daniel T. Riley
  #       text: Musician, songwriter, producer.
  #       image: assets/img/members/person6.jpg
  #       url: '#'
  #     - title: Ella P. Walter
  #       text: PR.
  #       image: assets/img/members/person7.jpg
  #       url: '#'

  # - type: timeline.html
  #   section_id: timeline
  #   title: Major Achievements!
  #   background_style: bg-dark text-primary
  #   last_image: assets/img/timeline-end.png
  #   actions:
  #     - image: assets/img/portfolio/thumbnails/1.jpg
  #       title: >+
  #         2017-2018
  #         **Humble Beginnings**
  #       text: >-
  #         We begun with small group of people willing to work hard and make our
  #         teaching skills worth , in front of all others!
  #     - image: assets/img/portfolio/thumbnails/2.jpg
  #       title: >+
  #         November 2019
  #         An Coaching started
  #       text: >-
  #         We started to gather like minded people and started our stategies
  #         and future plans to them. As a result , interested people joined us!

  - type: contact.html
    section_id: contacts
    title: Connect with me!
    text: #>-
      #Ready to start your next project with us? Give us a call or send us an email
      #and we will get back to you as soon as possible!
    actions:
    #- title: +1 (202) 555-014
    #  icon: fa-phone
    - title: E-Mail
      icon: fa-envelope
      url: mailto:theshirleyzhang@gmail.com
    - title: Linkedin
      icon: fa-linkedin
      icon_type: fab
      url: 'https://www.linkedin.com/in/shirley-shuocheng-zhang/'
    - title: Github
      icon: fa-github
      icon_type: fab
      url: 'https://github.com/shirleyzhang2'

---
