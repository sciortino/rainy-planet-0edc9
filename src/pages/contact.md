---
title: Get in Touch
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - type: form_field
    template: form_field
    input_type: text
    name: name
    label: Name
    default_value: Your name
    is_required: true
  - type: form_field
    template: form_field
    input_type: email
    name: email
    label: Email
    default_value: Your email address
    is_required: true
  - type: form_field
    template: form_field
    input_type: select
    name: subject
    label: Subject
    default_value: Please select
    options:
      - Error on the site
      - Sponsorship
      - Other
  - type: form_field
    template: form_field
    input_type: textarea
    name: message
    label: Message
    default_value: Your message
  - type: form_field
    template: form_field
    input_type: checkbox
    name: consent
    label: >-
      I understand that this form is storing my submitted information so I can
      be contacted.
submit_label: Send Message
template: contact
---

To get in touch fill the form below.
