---
title: Contact
sections:
  - type: hero_section
    title: Contact Me
    subtitle: >-
      Fill out the form below and I will get in touch within 1 business day.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >-
      ## Pricing

      After a short onboarding call I will be able to provide you with ballpark
      pricing, followed by a detailed proposal once we discuss the details. 

      ### Proposal

      Your proposal will include several choices in terms of pricing structure
      and deliverable timeline.

      ### Terms

      If at any point you'd like to cancel our project, you are required to
      provide a 30-day written notice, after which I will transfer all of your
      assets to you so you can use them anytime.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: og:type
      value: website
      keyName: property
    - name: og:title
      value: Contact
      keyName: property
    - name: og:description
      value: This is the contact page
      keyName: property
    - name: twitter:card
      value: summary
    - name: twitter:title
      value: Contact
    - name: twitter:description
      value: This is the contact page
layout: advanced
---
