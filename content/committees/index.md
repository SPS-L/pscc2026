---
# Leave the homepage title empty to use the site title
title: Call for Papers
date: 2025-01-24
type: landing

sections:

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
