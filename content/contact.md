---
title: Contact
hide_title: false
sections:
  - type: section_form
    section_id: contact-form
    content: To get in touch please fill the form below.
    form_id: contactForm
    form_action: /thank-you
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
          - I have a job for you
          - Let's collaborate and create music
          - I just want to talk
      - type: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Your message
        is_required: true
      - type: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
layout: advanced
---
