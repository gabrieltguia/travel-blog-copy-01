---
title: Contato
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - type: form_field
    input_type: text
    name: nome
    label: Nome
    default_value: Seu nome
    is_required: true
    options:
      - lorem-ipsum
  - type: form_field
    input_type: email
    name: email
    label: E-mail
    default_value: Seu endereço de e-mail
    is_required: true
  - type: form_field
    input_type: select
    name: subject
    label: Assunto
    default_value: Selecione
    options:
      - Orçamento
      - Dúvidas gerais
      - Reportar erro no site
      - lorem-ipsum
  - type: form_field
    input_type: textarea
    name: message
    label: Message
    default_value: Your message
  - type: form_field
    input_type: checkbox
    name: consent
    label: >-
      I understand that this form is storing my submitted information so I can
      be contacted.
submit_label: Send Message
template: contact
---
Para dúvidas/informações, preencha o formulário abaixo!
