---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: hero
    id: top
    content:
      title: Turn corrosion uncertainty into defensible service-life and maintenance decisions.
      text: >-
        RationalDurability Labs Inc. develops durability intelligence products that integrate multiphysics modelling,
        electrochemical corrosion analytics, and life-cycle cost optimization - so owners and engineers can prioritize
        interventions, reduce risk, and extend asset life in aggressive environments.
      primary_action:
        text: View the Durability Insight Assessment (DIA (TM))
        url: /#offer
      secondary_action:
        text: Request a scoping call
        url: /#contact
      announcement:
        text: Physics-informed modelling - Electrochemical data intelligence - Life-cycle decisions
    design:
      background:
        gradient_mesh:
          enable: true
          style: orbs
          intensity: subtle
          colors:
            - primary-500/25
            - secondary-500/20
      spacing:
        padding: ["4rem", 0, "2rem", 0]

  - block: stats
    id: highlights
    content:
      items:
        - statistic: "2-4 weeks"
          description: typical delivery window
        - statistic: "P10 / P50 / P90"
          description: probabilistic outputs
        - statistic: "Portfolio-ready"
          description: scales across assets
        - statistic: "Actionable"
          description: ranked interventions
    design:
      layout: cards
      spacing:
        padding: ["1rem", 0, "2rem", 0]

  - block: cta-card
    id: mvo
    content:
      title: Minimum viable offering
      text: >-
        The **Durability Insight Assessment (DIA (TM))** converts existing inspection and exposure data into
        quantified corrosion risk, service-life envelopes, and life-cycle cost trade-offs - without requiring new testing.
      button:
        text: View deliverables
        url: /#offer
    design:
      background:
        gradient:
          start: "primary-900"
          end: "secondary-900"
      card:
        text_color: light
        overlay_opacity: 0.2

  - block: features
    id: services
    content:
      title: Capabilities
      text: >-
        Integrated durability intelligence across reinforced concrete and metallic systems - connecting
        mechanisms, measured data, and decisions.
      items:
        - name: Multiphysics durability modelling
          icon: chart-bar
          description: >-
            Mechanism-based modelling of transport, electrochemistry, and damage.
            Includes chloride + carbonation + moisture coupling, crack-informed transport and corrosion behaviour,
            and scenario analysis for exposure and microclimate sensitivity.
        - name: Electrochemical data intelligence
          icon: beaker
          description: >-
            Structured interpretation of corrosion measurements and kinetics.
            Includes parameter extraction from polarization and scan data, material and fabrication factor ranking frameworks,
            and model-calibrated interpretation for real environments.
        - name: Life-cycle cost and risk optimization
          icon: calculator
          description: >-
            Probabilistic deterioration modelling translated into intervention priorities.
            Includes P10/P50/P90 service-life envelopes, do-nothing vs intervention scenario economics,
            and portfolio prioritization and maintenance scheduling.

  - block: cta-image-paragraph
    id: offer
    content:
      items:
        - title: "Minimum viable offering: Durability Insight Assessment (DIA (TM))"
          text: >-
            A standardized, model-driven decision product that converts existing information into clear,
            defensible service-life and maintenance guidance.
          feature_icon: check
          features:
            - "Corrosion risk profile - Dominant mechanisms and sensitivity drivers"
            - "Service-life envelope - Probabilistic life estimates (P10/P50/P90)"
            - "Life-cycle cost trade-offs - Timing-sensitive intervention economics"
            - "Prioritized actions - Ranked intervention classes and triggers"
        - title: Inputs
          text: >-
            DIA (TM) is designed to minimize barriers. It typically uses existing records and inspection data.
            No new testing is required for the base assessment.
            Optional add-ons can include targeted electrochemical interpretation, model calibration,
            or portfolio-scale screening.
          feature_icon: check
          features:
            - "Asset basics - Age, geometry, materials, and service requirements"
            - "Exposure classification - Chlorides, carbonation, moisture, temperature"
            - "Inspection / testing data - Condition surveys, cover, chloride, corrosion indicators"
            - "Decision horizon - Planning window (e.g., 20-50 years)"

  - block: features
    id: process
    content:
      title: Process
      text: >-
        A disciplined workflow designed for transparency and traceability - so results can be defended internally and externally.
      items:
        - name: Scope and data intake
          icon: clipboard-document-check
          description: Define asset boundaries, exposure assumptions, and decision horizon.
        - name: Model setup
          icon: squares-2x2
          description: Select mechanism set and parameter priors consistent with the environment.
        - name: Probabilistic evaluation
          icon: chart-pie
          description: Generate service-life envelopes and sensitivity drivers (P10/P50/P90).
        - name: Decision outputs
          icon: arrow-trending-up
          description: Translate model outputs into ranked actions and life-cycle cost trade-offs.

  - block: contact-info
    id: contact
    content:
      title: Request a scoping call
      subtitle: >-
        Provide a brief description of the asset type and environment. A structured intake template will be returned
        within one business day.
      connect_title: Engagement clarity
      text: >-
        What DIA (TM) is: a structured decision product based on modeling and data synthesis. What DIA (TM) is not:
        commodity testing, detailed design specifications, or construction oversight.
      show_form: true
      form_action: "#"
      prospective:
        title: Best-fit clients
        text: Owners, operators, consultants, asset managers
        button:
          text: Common outcomes
          url: /#contact
    design:
      spacing:
        padding: ["3rem", 0, "4rem", 0]
---
