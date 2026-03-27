---
# Leave the homepage title empty to use the site title
title: 'Contact'
summary: ''
date: 2026-01-05
type: landing

design:
  # Default section spacing
  spacing: '0'

sections:
  #- block: markdown
  #  content:
  #    title: Contact Me
  #    # subtitle: My subtitle
  #    text: | # Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  #  design:
  #    #columns: '1'
  #    background:
  #      color:
  #        light: "#ffffff"
  #        dark: "#0d0d12"
  #    #spacing:
  #    #  padding: ["4rem", "0", "4rem", "0"]
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
  - block: cta-card
    content:
      title: "Open to Opportunities"
      text: |-
        I'm looking for **Assistant Professor**, **Teaching Professor**, or **Postdoc** roles.
        <br />
        Let's connect!
      button:
        text: 'Download Resume'
        url: uploads/Heliodoro Tejeda - CV.pdf
        new_tab: true
    design:
      card:
        # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
  
---
