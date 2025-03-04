---
# Leave the homepage title empty to use the site title
title: Call for Papers
date: 2025-01-24
type: landing

sections:

  - block: hero
    content:
      title: Call for Papers
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
      text: "\n\n \n\n \n\n \n\n \n\n"
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
    id: scope
    content:
      title: Conference scope
      subtitle: 
      text: |-
        The Power Systems Computation Conference addresses theoretical developments and computational aspects with respect to power systems applications. There is an emphasis on modelling and simulation for understanding a system of components, plants or actors, the interactions between them and their collective behaviour, and methods to inform decision-making in power systems.

        Contributions might comment on the analytical techniques, modelling challenges and complex software engineering issues, or what the analyses say in respect of today's and future power systems challenges. Thus, papers from utility and manufacturing industry engineers are just as welcome as those from academic researchers.

        {{< cta cta_text="Submit abstract" cta_link="http://pscc.epfl.ch/" cta_new_tab="true" >}}

    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: topics
    content:
      title: List of topics
      subtitle: 
      text: |-
        The following list of topics is not exhaustive but is offered to help prospective authors identify what is likely to be in scope.

        ### Assessment of system issues in the presence of uncertainty or unbundling

        - Power system planning and operation
        - Asset management
        - Massive integration of renewable energy resources
        - Power system reliability and security
        - Uncertainty and risk management methods
        - Impact and management of extreme events
        - Pathways to zero carbon electricity systems

        ### Power system modeling, analysis, operation and control

        - Blackout prevention, system resilience and restoration
        - Control centre technologies and advanced operator tools
        - Wide-area monitoring and control
        - Power system dynamics
        - Power system protection
        - Power systems as part of multi-energy systems
        - Power systems and electro-mobility
        - Power system economics, energy markets and regulation
        - Distribution system monitoring, operation and control
        - Aggregation, disaggregation and control of distributed energy resources
        - Flexibility and demand-side management
        - Operation and control of HVDC systems and hybrid AC/DC transmission systems
        - System-wide electro-magnetic transients
        - Power quality
        - System integration and utilisation of energy storage systems
        - System integration of grid-connected power-electronic converters

        ### Integrated modelling and operation of information and communication technologies (ICT) in power systems

        - Cyber security in power systems operation and control
        - ICT-driven intelligent and autonomous controls
        - Modelling of cyber-physical energy and communication systems

        ### Data analysis and computation

        - Data-driven modelling techniques for power systems
        - Machine learning, statistics and computational intelligence
        - Management and utilization of big data
        - Mathematical and computational issues in modelling and simulation
        - Forecasting methods
        - Condition monitoring and diagnostics
        - Computational challenges in a digitalized grid

        ## The techniques considered include (but are not limited to):

        - Modelling and simulation
        - Optimization and mathematical programming
        - Uncertainty & risk management methods
        - Control theory and control frameworks
        - Signal processing
        - Machine learning, stochastic processes and statistics
        - Semantic web technologies
        - Parallel and distributed computing
        - Cost benefit analysis and financial appraisal
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: types
    content:
      title: Types of papers
      subtitle: 
      text: |-
        Four types of papers are sought:

        1. New approaches and techniques for modelling, analysis, or control of power systems or their components.
        2. Improvements in methodologies or modelling currently applied in the power system domain.
        3. Case studies and experience with implementations of new methodologies.
        4. Case studies and experience in application of computational methods to modern power systems challenges.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
  - block: markdown
    id: submission
    content:
      title: Submission procedure
      subtitle: 
      text: |-
        To submit your contributions please follow the instruction on the dedicated Submission Management System

        {style="padding-top: 2rem"}
        {{< table path="dates.csv" header="false" >}}

        {< cta cta_text="Submit abstract" cta_link="http://pscc.epfl.ch/" cta_new_tab="true" >}}
        
        Full paper submission instructions will be provided following acceptance of an abstract. Only electronically submitted abstracts and papers are considered.

        In order to be published in the final conference proceedings, all accepted papers must be presented at the conference by one of the named authors. English will be used for all printed material, as well as for the technical presentations and discussions.

        All accepted and presented papers will be posted publicly on the [PSCC website](https://pscc-central.epfl.ch/) and included in a special issue of the journal Electric Power Systems Research (EPSR) indexed by ScienceDirect. Accordingly, all authors must agree to the [EPSR copyright policies](https://www.elsevier.com/about/policies/copyright)
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
