---
title: Time to connect
sections:
  - type: hero_section
    title: Human connection must not be broken
    subtitle: Let us find time for one another, from a fellow being to another,
      sharing and exchanging openly
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
    content: ""
  - form_position: right
    form_layout: inline
    padding_top: medium
    align_vert: top
    form_width: fifty
    enable_card: true
    submit_label: Send Message
    form_action: /thank-you
    background_color: primary
    form_fields:
      - type: form_field
        input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - type: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - type: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - type: form_field
        input_type: checkbox
        name: consent
        label: I understand that this form is storing my submitted information so I can
          be contacted.
        is_required: true
    form_id: contact-form
    content: >-
      ### Don't be shy


      As we continue to promote causes and good works we believe in, we hope you don’t stop to fight for good either — you are not alone and we are more than happy to join forces with you, or just listen to your journey. Together we can make a difference!


      ### Email


      Email us at [mightystars.joanne@gmail.com](mailto:mightystars.joanne@gmail.com) or drop us a message using the form.
    padding_bottom: medium
    type: form_section
    content_align: left
seo:
  type: stackbit_page_meta
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: og:type
      value: website
      keyName: property
    - name: og:title
      value: General Enquiries
      keyName: property
    - name: og:description
      value: This is the general enquiries page
      keyName: property
    - name: twitter:card
      value: summary
    - name: twitter:title
      value: General Enquiries
    - name: twitter:description
      value: This is the general enquiries page
template: advanced
---
