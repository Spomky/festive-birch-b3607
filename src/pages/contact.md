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
    label: Courriel
    default_value: Votre adresse e-mail
    is_required: true
  - input_type: select
    name: subject
    label: Sujet
    default_value: Choisissez
    options:
      - Erreur sur le site
      - Parrainage / Partenariat
      - Autre
  - input_type: textarea
    name: message
    label: Message
    default_value: Votre message
  - input_type: checkbox
    name: consent
    label: >-
      En cochant cette case, je consens à transmettre les informations saisies
      sur ce formulaire et, éventuellement, à être recontacté(e).
submit_label: Envoyer
template: contact
---

Remplissez le formulaire pour me contacter.
