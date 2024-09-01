---
title: Home
slug: /
sections:
  - type: CarouselSection
    subtitle: 'Trending Films, Series, Books and Celebrities'
    items:
      - type: FeaturedItem
        title: Halle Berry New "Never Let Go"
        tagline: New Never Let Go chilling trailer gets released
        subtitle: ''
        text: "When an unspeakable evil takes over the world, the only protection for a mother and her twin sons is their house and strong bond. Needing to stay connected at all times -- even tethering themselves with ropes -- they must cling to one another and never let go. However, when one of the boys questions\_if the evil is real, the ties that bind them together are severed, triggering a terrifying fight for survival.\n"
        actions:
          - type: Button
            label: Watch Trailer
            altText: ''
            url: 'https://www.youtube.com/watch?v=-H3yhfkJBnQ'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
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
        image:
          type: ImageBlock
          url: /images/Design sem nome (1).png
          altText: Image alt text placeholder
          elementId: ''
          styles:
            self:
              borderRadius: medium
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: Testimonial 2
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/Design sem nome (2).png
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
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
        fontWeight: 500
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
