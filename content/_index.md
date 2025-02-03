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
      date: '2025-06-01 00:00:00'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: THE YEAR’S CAN’T-MISS EVENT FOR AI COLLABORATION
          text: AI Summit is coming home to San Francisco. Join us at AI Summit 2024 to explore all the cutting-edge innovation the data cloud has to offer.
          # Upload image to `assets/media/` and reference the filename here
          image: city-daniel-abadia.jpg
        - title: DISCOVER
          text: Discover the latest in AI, GenAI, application development and much more.
          # Upload image to `assets/media/` and reference the filename here
          image: conference-headway-F2KRf_QfCqw.jpg
        - title: HEAR FROM LEADERS REDEFINING THE AI LANDSCAPE
          text: Hear valuable insights from data and AI experts and business leaders, while discovering the limitless possibilities of data, AI and application collaboration for your organization.
          # Upload image to `assets/media/` and reference the filename here
          image: round-table-evangeline-shaw-xRlI-L-kvrw.jpg
          button:
            text: Get Tickets
            url: https://www.eventbrite.com/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: experience
    content:
      title: Important Dates
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2, 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: 
          company: Deadline for submission of one-page abstracts
          company_url: ''
          company_logo: 
          location: 
          date_start: '2025-06-30'
          date_end: '2025-06-30'
          description: ''
        - title: 
          company: Deadline for full paper submission
          company_url: ''
          company_logo: 
          location: 
          date_start: '2025-10-01'
          date_end: '2025-10-01'
          description: ''
        - title: 
          company: Authors notified about acceptance and required modifications
          company_url: ''
          company_logo: 
          location: 
          date_start: '2026-02-01'
          date_end: '2026-02-01'
          description: ''
        - title: 
          company: Final manuscript submission. 
          company_url: ''
          company_logo: 
          location: 
          date_start: '2026-03-15'
          date_end: '2026-03-15'
          description: ''
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: agenda
    content:
      title: Agenda
      text: |
        **DAY 1**
        {style="padding-top: 2rem"}
        {{< table path="schedule.csv" header="true" >}}
        
        **DAY 2**
        {style="padding-top: 2rem"}

        {{< table path="schedule.csv" header="true" >}}
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Alice Smith"
          role: "Researcher at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "It has to be the most insightful conference I've ever attended!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
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
  - block: newsletter
    content:
      title: "Stay up to date"
      text: "Be the first to receive conference updates such as added speakers, deadlines, and ticket deals."
      text_cta: "Sign up to our newsletter 🔥"
      button:
        text: "Subscribe"
      convertkit:
        form_id: ''
        msg_subscribed: "Success! Please check your email to confirm your subscription."
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
