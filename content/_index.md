---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      eyebrow: Diagnostic Assessment and Achievement of College Skills
      title: Rethinking College Readiness
      text: DAACS is a suite of technological and social supports shown to increase student success.
      primary_action:
        text: Try DAACS
        url: "https://my.daacs.net"
        icon: rocket-launch
        style: gradient
      secondary_action:
        text: How it works
        url: "#how-it-works"
        icon: play-circle
        style: ghost
#      announcement:
#        badge:
#          text: NEW
#          color: primary
#        text: AI roadmap pull is live.
#        link:
#          text: Read more
#          url: "#features"
      trust:
#        stars: 5
        text: "Used by more than 100,000 students"
      # To switch to a split layout with a product mockup, uncomment the media block
      # below and set `design.layout: split-left` (or `split-right` / `stacked`):
      # media:
      #   type: image
      #   src: dashboard.png
      #   dark_src: dashboard-dark.png   # optional dark-mode variant
      #   alt: Beacon dashboard
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      section_break:
        # Fade the hero's bottom edge into the dark logos band beneath (matches its bg-gray-900)
        fade_bottom: "#101828"
      background:
        # Deep navy base; radial glow paints a soft violet spotlight from above
        color: "#411244"
        gradient:
          type: radial
          start: "rgba(124,58,237,0.45)"
          end: "transparent"
          position: "50% -10%"
          shape: ellipse
          size: "80% 80%"
        # Mesh orbs add depth and atmosphere on top of the radial glow
        gradient_mesh:
          enable: true
          style: orbs
          intensity: medium
          animation: pulse
          colors: ["primary-500/25", "secondary-500/25"]
          orb_count: 2
          positions: ["top-1/3 left-1/4", "bottom-1/3 right-1/4"]
          sizes: ["w-[32rem] h-[32rem]", "w-[26rem] h-[26rem]"]
#  - block: logos
#    content:
#      title: Institutional partners
#      items:
#        - icon: brands/github
#          name: GitHub
#        - icon: brands/google
#          name: Google
#    design:
#      layout: marquee
#      # White logos read cleanly against the dark band; both styles work — see logos block schema
#      logo_style: white
#      logo_size: md
#      marquee_speed: 35
#      # `dark` activates child components' `dark:` variants, `bg-gray-900` paints the band.
#      # Extends the dark zone from the hero, so the hero's fade-bottom no longer reveals a light strip.
#      css_class: "dark bg-gray-900"
#      spacing:
#        padding: ["2rem", 0, "2rem", 0]
#  - block: stats
#    content:
#      items:
#        - statistic: "12k+"
#          description: |
#            Signals captured  
#            per day
#        - statistic: "85%"
#          description: |
#            Less time spent  
#            triaging feedback
#        - statistic: "3.2×"
#          description: |
#            Faster roadmap  
#            decisions
#    design:
#      layout: minimal
#      numbers_gradient: true
#      css_class: "bg-white dark:bg-gray-900"
#      spacing:
#        padding: ["3rem", 0, "3rem", 0]
  - block: steps
    id: how-it-works
    content:
      title: A formative assessment platform designed for student feedback
#      text: Get insights in your first week. No strategy doc required.
      items:
        - title: RETHINKING COLLEGE READINESS
          text: In the past, newly enrolled college students had little reliable information about their readiness for college-level academic work. DAACS addresses this problem by providing students with detailed information and feedback on their preparation for college, as well as resources for shoring it up. By using DAACS, students can build needed skills in areas of self-regulated learning, writing, reading, and mathematics while enrolled in courses that lead to the completion of their degrees.
          icon: school
        - title: FOCUSSING ON THE WHOLE STUDENT
          text: Current research suggests that self-regulated learning, mindset, and motivation are better predictors of college success than traditional placement or entrance exams. DAACS places emphasis on these areas and provides students with concrete strategies for becoming a more successful college student.
          icon: user-graduate
        - title: PREDICTIVE ANALYTICS
          text: Data provided by DAACS has been shown to increase the efficacy of predictive analytic models. These data not only help institutions identify their most academically at-risk students, but also provide specific information as to how they are at risk. With this information, more targeted interventions can be developed that better serve students’ needs.
          icon: chart-line
    design:
      layout: horizontal
      marker_style: icon
      connector: none

  - block: features
    id: features
    content:
      subtitle: Why DAACS
      title: Customer voice, organized
      text: Stop chasing feedback across five tools. Let Beacon do the listening, the synthesis, and the routing.
      items:
        - name: AI signal synthesis
          icon: sparkles
          description: Beacon clusters thousands of fragmented signals into clear themes, ranked by frequency, recency, and revenue weight. Stop sifting; start shipping.
        - name: Realtime capture
          icon: bolt
          description: From Slack threads to support tickets to in-app surveys — every channel, one inbox, instantly.
        - name: Smart segmentation
          icon: rectangle-group
          description: Slice feedback by plan tier, persona, region, or any custom property in seconds.
        - name: Roadmap sync
          icon: arrow-path
          description: Push prioritized themes straight into Linear, Jira, or Notion — round-trip status updates included.
        - name: Branded widget
          icon: paint-brush
          description: Match your product's design tokens. Custom CSS supported. Ship a widget that looks like yours.
        - name: SOC 2 + GDPR
          icon: shield-check
          description: Enterprise-grade security and data residency from day one. We never train models on customer data.
    design:
      layout: bento
      css_class: "bg-gray-50 dark:bg-gray-900/50"
  - block: comparison-table
    id: compare
    content:
      subtitle: How we compare
      title: Why teams switch to Beacon
      text: We picked the categories that matter to teams shipping today.
      competitors:
        - name: Beacon
          tagline: AI feedback platform
          highlight: true
          badge: Recommended
        - name: Canny
          tagline: Feedback boards
        - name: UserVoice
          tagline: Enterprise voice-of-customer
        - name: Productboard
          tagline: Product management suite
      rows:
        - feature: Capture
          category: true
        - feature: Channel coverage
          note: Slack, email, in-app, support
          values: ["30+", "Limited", "Limited", "Some"]
        - feature: Auto-capture from Slack
          values: [true, false, false, "limited"]
        - feature: In-app widget
          values: [true, true, true, true]
        - feature: Synthesis
          category: true
        - feature: AI clustering
          values: [true, "partial", false, "partial"]
          highlight: true
        - feature: Theme detection
          values: [true, false, false, true]
        - feature: Sentiment analysis
          values: [true, false, true, true]
        - feature: Cost & ownership
          category: true
        - feature: Free tier
          values: [true, true, false, false]
        - feature: Starting price
          values: ["Free", "$50/mo", "$499/mo", "$59/mo"]
        - feature: Roadmap integrations
          values: [true, "limited", true, true]
      cta:
        text: Start free
        url: "#pricing"
        icon: hero/arrow-right
    design:
      row_striping: true
      css_class: "bg-gray-50 dark:bg-gray-900/50"

  - block: pricing
    id: pricing
    content:
      title: "Pricing"
      subtitle: "Always free for individual students."
      billing_toggle:
        enabled: false
        monthly_label: Monthly
        yearly_label: Yearly
        yearly_discount: "Save 20%"
      tiers:
        - name: Students
          description: "Students can assess their college readiness."
          price:
#            monthly: "0"
            yearly: "0"
            currency: "$"
          price_note: "Free forever"
          highlight: false
          cta:
            text: Take DAACS now
            url: "https://my.daacs.net"
            icon: hero/arrow-right
            style: outline
          features:
            - text: "Self-Regulated Learning Assessment"
              included: true
            - text: "Personalized feedback and links to OERs (including the SRL lab)"
              included: true
            - text: "Demo versions of the writing, reading, and mathematics"
              included: true
            - text: "Individual student summary reports"
              included: false
#            - text: AI clustering
#              included: false
#            - text: Priority support
#              included: false
        - name: Instructors
#          badge: Most popular
          description: "Classrooms for your students."
          price:
#            monthly: "19"
            yearly: "100"
            currency: "$"
          price_suffix: /classroom
#          price_note_monthly: "Billed monthly"
          price_note_yearly: "Billed per classroom up to 35 students"
          highlight: false
          cta:
            text: Contact for more information
            url: "mailto:sales@daacs.net"
            icon: hero/arrow-right
            style: outline
          features:
            - text: Classroom dashboard with analytics
              included: true
            - text: "Individual student summary reports"
              included: true
            - text: Students have access to all SRL, writing, math, and reading assessments
              included: true
            - text: DATA exports
              included: true
            - text: Ability to create custom assessments
              included: true
        - name: Institutions
          description: "Custom DAACS instance to match your institutional branding and goals."
          price:
#            monthly: "49"
            yearly: "20,000"
            currency: "$"
          price_suffix: /year
#          price_note_monthly: "Billed monthly"
          price_note_yearly: "Billed annually"
          highlight: false
          cta:
            text: Email to schedule an demo
            url: "mailto:sales@daacs.net"
            icon: email
            style: outline
          features:
            - text: Personalized DAACS instance
              included: true
            - text: "All classroom features"
              included: true
            - text: SSO and LTI integrations
              included: true
            - text: Access to worksheets, trainings, and online community
              included: true
            - text: API access to data
              included: true
            - text: Priority support
              included: true

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Built for makers shipping fast
          text: Beacon meets you where your customers already are. Drop in the widget, sync your tools, and watch themes emerge in your first week.
          feature_icon: check
          features:
            - "One-line install (JS snippet or SDK)"
            - "30+ integrations out of the box"
            - "AI synthesis from day one"
          # Pexels — Rodrigo Santos / photo 3888151 (free for commercial use)
          image: makers-shipping.jpg
          button:
            text: Start free
            url: "#pricing"
        - title: Loved by product and support teams
          text: Bring product, support, and engineering to the same table. Beacon turns scattered feedback into shared truth — backed by data, not opinions.
          feature_icon: bolt
          features:
            - "Slack, Zendesk, Intercom, and Linear sync"
            - "Custom roles, audit logs, and SSO"
            - "Round-trip roadmap status updates"
          # Pexels — Anna Shvets / photo 5716018 (free for commercial use)
          image: teams-collaboration.jpg
          button:
            text: Book a demo
            url: "https://beacon.example.com/demo"
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Student"
#          role: "Head of Product at Loop"
          # Upload image to `assets/media/` and reference the filename here
#          image: "testimonial-1.jpg"
          text: "Thanks for the Self-regulated test, it has given me the knowledge need to know the areas I need to improve in. I know the areas that I am strong in but could still learn more. This test has help we to see that I am ready to start classes eager to start to learn more. I am excited to start class to learn new things to build my knowledge that will lead me to my dream career and all my goals in life."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]

#  - block: faq
#    id: faq
#    content:
#      title: Frequently asked questions
#     subtitle: Everything you need to know before getting started.
#      items:
#        - question: Where is my data hosted?
#          answer: |
#            We default to AWS `us-east-1`, with EU and APAC residency available on Business plans. Beacon is SOC 2 Type II certified and GDPR-compliant — and we never train models on your customer data.
#        - question: Which tools does Beacon integrate with?
#          answer: |
#            30+ integrations across Slack, Linear, Notion, Zendesk, Intercom, Jira, HubSpot, and more. Don't see yours? The Webhooks API takes 5 minutes to wire up.
#        - question: How does the AI clustering work?
#          answer: |
#            Beacon embeds every signal, clusters by semantic similarity, and surfaces themes ranked by frequency, recency, and revenue weight. You see clusters — not raw transcripts — within minutes of installing.
#        - question: Can I migrate from Canny or UserVoice?
#          answer: |
#            Yes. Our import takes a CSV or API key, preserves voter and comment history, and runs in under 10 minutes for most teams. We'll do the migration for you on Business plans.
#        - question: What's the free tier limit?
#          answer: |
#            Up to 5 seats and 500 signals per month, with all core capture and triage features. The free tier doesn't expire.
#        - question: Do you have an SLA?
#          answer: |
#            99.9% uptime SLA on Team and Business plans. Public status page, real-time incident notifications, and post-mortems baked in.

  - block: cta-card
    content:
      title: A better way to assess college readiness and provide students the supports they need
      text: Free for individual students, inexpensive for instructors and institutions
      button:
        text: Try DAACS
        url: "https://my.daacs.net"
    design:
      section_break:
        # Fade the cta-card section's top edge into the white FAQ section above
        fade_top: "#411244"
      card:
        # Brand-coloured card with subtle gradient depth
        css_class: "bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl"
        css_style: ""
---
