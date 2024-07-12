---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Welcome to my portfolio website!
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: left
    subtitle: Innovative. Analytical. Driven.
    text: ''
    actions:
      - type: Link
        altText: LinkedIn
        url: 'https://www.linkedin.com/in/ben-lopez-ba-msc-15041a223/'
        showIcon: true
        icon: linkedin
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        altText: GitHub
        url: 'https://github.com/Ben-s-v-Lopez'
        showIcon: true
        icon: github
        iconPosition: left
        style: secondary
        elementId: ''
      - label: Projects
        altText: ''
        url: /blog
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      styles:
        self:
          borderRadius: medium
          padding:
            - pl-0
            - pt-0
            - pr-0
          margin:
            - ml-48
            - mr-48
            - mb-0
            - mt-0
      url: /images/2330859 1.jpg
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Data Scientist
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Innovating with Machine Learning and Analytics
    text: >
      A London based data scientist. I hold a Master's degree in Data Science &
      Analytics from Brunel University and a Bachelor's degree in Marketing from
      Richmond American University. My work focuses on integrating machine
      learning and data analytics to drive innovative business solutions.


      I'm passionate about using tech to tackle real world problems. My
      experience is in bioinformatics, ESG analytics, climate science, and the
      financial markets.
    badge:
      label: Key insights of a
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
        padding:
          - pt-12
          - pb-12
      subtitle:
        textAlign: center
    type: GenericSection
  - type: CarouselSection
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Machine learning and AI in BioTech
        tagline: Industry interests
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: Industry interests
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Business Consulting
        tagline: Feature 2
        subtitle: Be in good company
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Business consulting
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    title:
      type: TitleBlock
      text: ''
      color: text-dark
      styles:
        self:
          textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
