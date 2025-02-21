---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Ciao! Sono Betty Tealdo.
      color: text-dark
    subtitle: ''
    text: >+
      Se sei tornato/a per acquistare di nuovo, sono felicissima di averti come
      cliente fedele. Qui troverai gli stessi prodotti che ti sono piaciuti, ma
      anche tante novità. Se hai bisogno di aiuto o di consigli, sono sempre a
      tua disposizione!"

    actions:
      - type: Button
        label: Tutti i SuperFood
        url: /prodotti
        icon: arrowRight
        iconPosition: right
        style: secondary
        altText: Tutti i SuperFood
      - type: Button
        label: Contattami
        altText: Contattami
        url: /contatti
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/abstract-feature2.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: FeaturedPeopleSection
    people:
      - content/data/person1.json
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: Nome
          label: Nome
          hideLabel: true
          placeholder: Nome
          isRequired: true
          width: full
          type: TextFormControl
        - name: La tua email
          label: La tua email
          hideLabel: true
          placeholder: La tua email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: messaggio
          label: Messaggio
          hideLabel: true
          placeholder: Il tuo messaggio
          width: full
          type: TextareaFormControl
          isRequired: true
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Invia
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
