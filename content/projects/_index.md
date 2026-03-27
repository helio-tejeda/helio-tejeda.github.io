---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: research-areas
    content:
      title: Research Topics
      items:
        - name: Human-AI Collaboration
          #description: Human + AI Working Together
          icon: hero/cpu-chip
          gradient: from-blue-400 to-purple-600
        - name: AI-Assisted Decision-Making
          #description: Human + AI Joint Decision-Making
          icon: hero/cpu-chip-solid
          gradient: from-green-400 to-teal-600
        #- name: Artificial Intelligence
        #  description: Building next-generation AI systems
        #  icon: hero/cpu-chip
        #  gradient: from-blue-500 to-indigo-600
    # ... rest of configuration
    design:
      layout: hexagon
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  - block: collection
    content:
      title: Selected Projects
      text: Coming Soon...
      filters:
        folders:
          - projects
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
---
