---
# Leave the homepage title empty to use the site title
title: Call for Papers
date: 2025-01-24
type: landing

sections:
  - block: hero
    content:
      title: Committees
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
      text: "<br> <br> <br> <br> <br>"
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
    id: local
    content:
      title: Local Organizing Committee
      text: |
        {style="padding-top: 2rem"}
        {{< table path="local.csv" header="true" >}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: board
    content:
      title: PSCC Executive Board
      text: |
        {style="padding-top: 2rem"}
        {{< table path="executive.csv" header="true" >}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: markdown
    id: tpc
    content:
      title: Technical Program Committee
      text: |
        {style="padding-top: 2rem"}
        {{< table path="TPC.csv" header="true" >}}
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---
