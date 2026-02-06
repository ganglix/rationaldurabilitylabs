---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:

  # --------------------------------------------------
  # HERO
  # --------------------------------------------------
  - block: hero
    id: top
    content:
      title: Turn corrosion uncertainty into defensible service-life decisions.
      text: >-
        We quantify corrosion risk, service-life, and life-cycle deterioration
        so owners and engineers can time interventions with confidence.
      primary_action:
        text: View the Durability Insight Assessment (DIA™)
        url: /#offer
      secondary_action:
        text: Request a scoping call
        url: /#contact
      announcement:
        text: Physics-informed modelling • Electrochemical data intelligence • Life-cycle decisions
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

  # --------------------------------------------------
  # HIGHLIGHTS
  # --------------------------------------------------
  - block: stats
    id: highlights
    content:
      items:
        - statistic: "2–4 weeks"
          description: typical delivery
        - statistic: "P10 / P50 / P90"
          description: probabilistic outputs
        - statistic: "Portfolio-ready"
          description: scalable across assets
        - statistic: "Actionable"
          description: ranked decisions
    design:
      layout: cards
      spacing:
        padding: ["1rem", 0, "2rem", 0]

  # --------------------------------------------------
  # MVO CTA
  # --------------------------------------------------
  - block: cta-card
    id: mvo
    content:
      title: Minimum viable offering
      text: >-
        The **Durability Insight Assessment (DIA™)** transforms existing asset data
        into quantified corrosion risk, service-life envelopes, and intervention timing and effectiveness trade-offs.
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

  # --------------------------------------------------
  # CAPABILITIES
  # --------------------------------------------------
  - block: features
    id: services
    content:
      title: Capabilities
      text: Integrated durability intelligence for concrete and metallic infrastructure.
      items:
        - name: Multiphysics durability modelling
          icon: chart-bar
          description: Mechanism-based models linking transport, electrochemistry, and damage.
          points:
            - Chloride, carbonation, and moisture coupling
            - Crack-informed corrosion behaviour
            - Exposure and microclimate sensitivity
        - name: Electrochemical data intelligence
          icon: beaker
          description: Structured interpretation of corrosion measurements and kinetics.
          points:
            - Parameter extraction from polarization data
            - Material and fabrication ranking
            - Environment-calibrated interpretation
        - name: Life-cycle deterioration & intervention optimization
          icon: calculator
          description: Probabilistic deterioration modelling translated into targeted, effective intervention strategies.
          points:
            - P10 / P50 / P90 service-life envelopes
            - Intervention timing and effectiveness comparison
            - Portfolio-level prioritization under uncertainty

  # --------------------------------------------------
  # OFFER
  # --------------------------------------------------
  - block: cta-image-paragraph
    id: offer
    content:
      items:
        - title: Durability Insight Assessment (DIA™)
          text: >-
            A standardized, model-driven decision product for service-life and
            maintenance planning—no new testing required.
          feature_icon: check
          features:
            - Corrosion risk profile - Dominant mechanisms and sensitivity drivers
            - Probabilistic service-life envelope - P10/P50/P90 service-life projections
            - Intervention timing and effectiveness comparison - Timing-sensitive intervention strategy comparison
            - Prioritized intervention actions - Ranked intervention classes and triggers

        - title: Required inputs
          text: >-
            DIA™ uses information typically already available to owners and consultants.
          feature_icon: check
          features:
            - Asset basics - Age, geometry, materials, and service requirements
            - Exposure classification - Chlorides, carbonation, moisture, temperature
            - Inspection / testing data - Condition surveys, cover, chloride, corrosion indicators
            - Decision horizon - Planning window (e.g., 20-50 years)

  # --------------------------------------------------
  # PROCESS
  # --------------------------------------------------
  - block: features
    id: process
    content:
      title: Process
      text: A transparent workflow designed for traceable, defensible results.
      items:
        - name: Scope and data intake
          icon: clipboard-document-check
          description: Define asset boundaries, exposure, and planning horizon.
        - name: Model setup
          icon: squares-2x2
          description: Select mechanisms and parameter priors.
        - name: Probabilistic evaluation
          icon: chart-pie
          description: Generate service-life and sensitivity envelopes.
        - name: Decision outputs
          icon: arrow-trending-up
          description: Translate results into ranked actions and timing.

  # --------------------------------------------------
  # FAQ (NEW)
  # --------------------------------------------------
  - block: faq
    id: faq
    content:
      title: Frequently asked questions
      items:
        - question: What is DIA™?
          answer: >-
            DIA™ is a model-driven durability and life-cycle decision assessment.
            It converts existing asset data into quantified corrosion risk,
            service-life projections, and prioritized maintenance actions.

        - question: What is DIA™ not?
          answer: >-
            DIA™ is not a commodity testing service, detailed design specification,
            or construction oversight engagement.

        - question: Does DIA™ require new testing?
          answer: >-
            No. The base assessment uses existing inspection, condition,
            and exposure data. Optional add-ons may include targeted data interpretation
            or calibration if needed.

        - question: Who is DIA™ for?
          answer: >-
            Infrastructure owners, operators, consultants, and asset managers
            responsible for corrosion-critical concrete or metallic assets.

        - question: What do clients typically use DIA™ for?
          answer: >-
            Prioritizing maintenance, justifying intervention timing,
            screening asset portfolios, and supporting capital planning decisions.

  # --------------------------------------------------
  # CONTACT
  # --------------------------------------------------
  - block: contact-info
    id: contact
    content:
      title: Request a scoping call
      subtitle: >-
        Briefly describe the asset type and environment.
        A structured intake template will be returned within one business day.
      show_form: true
      form_action: "#"
      prospective:
        title: Best-fit clients
        text: Owners, operators, consultants, asset managers
---
