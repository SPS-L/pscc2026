---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: PSCC 2026
      text: ""
      details: "The Power Systems Computation Conference addresses theoretical developments and computational aspects with respect to power systems applications. There is an emphasis on modelling and simulation for understanding a system of components, plants or actors, the interactions between them and their collective behaviour, and methods to inform decision-making in power systems.\n\n Contributions might comment on the analytical techniques, modelling challenges and complex software engineering issues, or what the analyses say in respect of today’s and future power systems challenges. Thus, papers from utility and manufacturing industry engineers are just as welcome as those from academic researchers. \n\n Information on the previous edition can be found at [PSCC2024 – Power Systems Computation Conference](https://pscc2024.fr/)"
      primary_action:
        text: Call for Papers
        url: https://pscc2026.cy/call
        icon: ticket
      items:
        - name: "Speakers"
          description: "240"
        - name: "Attendees"
          description: "400+"
        - name: "Venue"
          description: "St Raphael Resort"
        - name: "Location"
          description: "Limassol, Cyprus"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
#      background:
#        color: ""
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: countdown
    content:
      title: "Call for Papers ends in"
      text: ""
      text_after: ""
      date: '2025-06-30 00:00:00'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: markdown
    id: dates
    content:
      title: Important Dates
      text: |
        {style="padding-top: 2rem"}
        |June 30th, 2025|:Deadline for submission of one-page abstracts.|
        |October 1st, 2025|:Deadline for full paper submission.|
        |February 1st, 2026|:Authors notified about acceptance and required modifications.|
        |March 15th, 2026|:Final manuscript submission.|

  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: 'TBA'
  - block: logos
    content:
      title: "Sponsors Making This Possible"
      text: "Thanks to the following sponsors for making this incredible event possible!"
      # Image path relative to assets/media/ folder
      logo_folder: 'sponsors/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
