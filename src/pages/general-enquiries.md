---
sections:
  - align: center
    background_color: none
    padding_bottom: medium
    padding_top: medium
    subtitle: The optional subtitle
    title: This is the Hero
    type: hero_section
  - align_vert: top
    background_color: primary
    content: >-
      ### Billing

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.

      ### Privacy

      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    content_align: left
    enable_card: true
    form_action: /thank-you
    form_fields:
      - default_value: Your name
        input_type: text
        is_required: true
        label: Name
        name: name
        type: form_field
      - default_value: Your email address
        input_type: email
        is_required: true
        label: Email
        name: email
        type: form_field
      - default_value: Please select
        input_type: select
        label: Subject
        name: subject
        options:
          - Error on the site
          - Sponsorship
          - Other
        type: form_field
      - default_value: Your message
        input_type: textarea
        label: Message
        name: message
        type: form_field
      - input_type: checkbox
        is_required: true
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        name: consent
        type: form_field
    form_id: contact-form
    form_layout: inline
    form_position: right
    form_width: fifty
    padding_bottom: medium
    padding_top: medium
    submit_label: Send Message
    type: form_section
stackbit_url_path: /general-enquiries
template: advanced
title: General enquiries
---
