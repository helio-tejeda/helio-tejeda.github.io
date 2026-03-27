---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

design:
  # Default section spacing
  spacing: '0'

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I research"
        strings:
          - "human-AI collaboration"
          - "AI-assisted decision-making"
          #- "beautiful UIs"
          #- "open source tools"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: Download CV
          url: uploads/Heliodoro Tejeda - CV.pdf
          icon: academicons/cv-square
        - text: View My Work
          url: https://scholar.google.com/citations?user=EKvwKb4AAAAJ&hl=en
          icon: academicons/google-scholar
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  #- block: stats
  #  content:
  #    items:
  #      - statistic: "$2.5M"
  #        description: Funding raised
  #        icon: hero/banknotes
  #      - statistic: "10K+"
  #        description: Active users
  #        icon: hero/users
  #      - statistic: "98.5%"
  #        description: Uptime reliability
  #        icon: hero/chart-line
  #  design:
  #    layout: minimal

  # Experience Timeline
  - block: resume-experience
    id: experience
    content:
      title: Experience
      # Change this to true to list Education first
      is_education_first: true
      date_format: Jan 2006
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Filterable Portfolio - Alpine.js powered project filtering
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: "Featured Projects"
  #    subtitle: "A selection of my recent work"
  #    count: 0
  #    filters:
  #      folders:
  #        - projects
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Full-Stack
  #        tag: Full-Stack
  #      - name: Frontend
  #        tag: Frontend
  #      - name: Backend
  #        tag: Backend
  #    default_button_index: 0
  #    # Archive link auto-shown if more projects exist than 'count' above
  #    # archive:
  #    #   enable: false  # Set to false to explicitly hide
  #    #   text: "Browse All"  # Customize text
  #    #   link: "/work/"  # Custom URL
  #  design:
  #    columns: 3
  #    background:
  #      color:
  #        light: "#ffffff"
  #        dark: "#0d0d12"
  #    spacing:
  #      padding: ["4rem", "0", "4rem", "0"]
  
  # Visual Tech Stack - Icons organized by category
  - block: tech-stack
    id: skills
    content:
      title: "Tech Stack"
      subtitle: "Technologies I use to build things"
      categories:
        - name: Programming Languages
          items:
            - name: Python
              icon: devicon/python
            - name: MATLAB
              icon: devicon/matlab
            - name: Java
              icon: devicon/java
            - name: C/C++
              icon: devicon/cplusplus
        - name: Databases
          items:
            - name: MySQL
              icon: devicon/mysql
            - name: PostgreSQL
              icon: devicon/postgresql
            - name: SQLite
              icon: devicon/sqlite
            - name: BigQuery
              icon: devicon/googlecloud
            - name: Firebase
              icon: devicon/firebase
        - name: Web Development
          items:
            - name: HTML
              icon: devicon/html5
            - name: CSS
              icon: devicon/css3
            - name: JavaScript
              icon: devicon/javascript
            - name: D3.js
              icon: devicon/d3js
            - name: PHP
              icon: devicon/php
            - name: Heroku
              icon: devicon/heroku
            - name: Hugo
              icon: brands/hugo
        - name: Python Toolkit
          items:
            - name: PyTorch
              icon: devicon/pytorch
            - name: Tensorflow
              icon: devicon/tensorflow
            - name: OpenCV
              icon: devicon/opencv
            - name: Scikit-Learn
              icon: devicon/scikitlearn
            - name: Matplotlib
              icon: devicon/matplotlib
            - name: NumPy
              icon: devicon/numpy
            - name: Pandas
              icon: devicon/pandas
            - name: Jupyter
              icon: devicon/jupyter
        #- name: Frontend
        #  items:
        #    - name: React
        #      icon: devicon/react
        #    - name: Next.js
        #      icon: devicon/nextjs
        #    - name: Tailwind CSS
        #      icon: devicon/tailwindcss
        #    - name: Alpine.js
        #      icon: devicon/alpinejs
        #- name: Backend
        #  items:
        #    - name: Node.js
        #      icon: devicon/nodejs
        #    - name: Express
        #      icon: devicon/express
        #    - name: PostgreSQL
        #      icon: devicon/postgresql
        #    - name: Redis
        #      icon: devicon/redis
        #- name: DevOps
        #  items:
        #    - name: Docker
        #      icon: devicon/docker
        #    - name: AWS
        #      icon: devicon/amazonwebservices-wordmark
        #    - name: GitHub Actions
        #      icon: brands/github
        #    - name: Vercel
        #      icon: devicon/vercel
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: resume-languages
    content:
      title: Languages
      username: me
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  # Recent Blog Posts
  - block: collection
    id: news
    content:
      title: News
      #subtitle: 'Thoughts on web development, tech, and more'
      text: ''
      filters:
        folders:
          - news
        exclude_featured: false
      count: 1
      order: desc
    design:
      view: card
      columns: 3
      #background:
      #  color:
      #    light: "#f5f5f5"
      #    dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publications
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: ''
  #    filters:
  #      folders:
  #        - publications
  #      exclude_featured: false
  #  design:
  #    view: citation
  
  # Contact Section
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's build something amazing together"
      text: |-
        I'm always interested in hearing about new projects and opportunities.
        Whether you're looking to hire, collaborate, or just want to say hi, feel free to reach out!
      email: htejeda@uci.edu
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # CTA Card
  #- block: cta-card
  #  content:
  #    title: "Open to Opportunities"
  #    text: |-
  #      I'm looking for **Assistant Professor**, **Teaching Professor**, or **Postdoc** roles.
  #      <br />
  #      Let's connect!
  #    button:
  #      text: 'Download Resume'
  #      url: uploads/Heliodoro Tejeda - CV.pdf
  #      new_tab: true
  #  design:
  #    card:
  #      # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
  #      css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
  #      text_color: dark
  #    background:
  #      color:
  #        light: "#f5f5f5"
  #        dark: "#08080c"
  #    spacing:
  #      padding: ["4rem", "0", "6rem", "0"]
---
