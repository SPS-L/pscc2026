---
# Leave the homepage title empty to use the site title
title:
date: 2024-11-24
type: landing

sections:

  - block: hero
    content:
      title: XXIV Power Systems Computation Conference
      image:
        # Reference an image in your `assets/media/` folder
        filename: 
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: 
        url: 
        #icon_pack: fas
        #icon: download
      # Optionally, add an alternative CTA link
      cta_alt:
        label: 
        url: 
      # Optionally, add a note under the Call-To-Action button
      cta_note:
        label:       
      # Add your Hero text here
      text: "8-12 June, 2026 <br> Limassol, Cyprus <br> <br> <br>"
    design:
      css_class: dark
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: welcome.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
  - block: markdown
    id: about
    content:
      title: Welcome Message
      subtitle: 
      text: "The Power Systems Computation Conference addresses theoretical developments and computational aspects of electric power systems research, with applications ranging from micro-grids to mega-grids. There is an emphasis on modelling and simulation for understanding a system of components, power plants and distributed energy conversion resources, or actors, the interactions between them and their collective behaviour, and methods to inform decision-making in power systems.\n\n Contributions may focus on analytical techniques, modelling challenges, complex software engineering issues and experimental studies as well as analyses with respect to today’s and the future’s power system challenges. Thus, papers from utility and manufacturing industry engineers are just as welcome as those from academic researchers.\n\n Information on the previous edition can be found at [PSCC2024 – XXIII Power Systems Computation Conference](https://pscc2024.fr/)"
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: dates
    content:
      title: Important Dates
      text: |
        {style="padding-top: 2rem"}
        {{< table path="dates.csv" header="false" >}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: portfolio
    id: venue
    content:
      title: Venue, City and Country
      subtitle: 
      text: 
      filters:
        # Folders to display content from
        folders:
          - venue
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: logos
    content:
      title: Organizing Institutes
      subtitle: 
      # Path to the logo images within the `assets/media/` folder
      logo_folder: orglogos
    design:
      columns: '1'    
---
