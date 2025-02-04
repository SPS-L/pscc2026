---
# Leave the homepage title empty to use the site title
title: Call for Papers
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
      text: "8-12 June, 2026\n\nLimassol, Cyprus\n\n"
    design:
      css_class: dark
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: img/pylons.jpg
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
      text: "The Power Systems Computation Conference addresses theoretical developments and computational aspects with respect to power systems applications. There is an emphasis on modelling and simulation for understanding a system of components, plants or actors, the interactions between them and their collective behaviour, and methods to inform decision-making in power systems.\n\n Contributions might comment on the analytical techniques, modelling challenges and complex software engineering issues, or what the analyses say in respect of today’s and future power systems challenges. Thus, papers from utility and manufacturing industry engineers are just as welcome as those from academic researchers. \n\n Information on the previous edition can be found at [PSCC2024 – XXIII Power Systems Computation Conference](https://pscc2024.fr/)"
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
---
