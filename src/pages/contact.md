---
title: Me contacter
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Nom
    default_value: Votre nom
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Votre adresse e-mail
    is_required: true
  - input_type: select
    name: subject
    label: Subject
    default_value: Please select
    options:
      - Error on the site
      - Sponsorship
      - Other
  - input_type: textarea
    name: message
    label: Message
    default_value: Your message
  - input_type: checkbox
    name: consent
    label: >-
      I understand that this form is storing my submitted information so I can
      be contacted.
submit_label: Send Message
template: contact
---

Remplissez le formulaire pour me contacter.
