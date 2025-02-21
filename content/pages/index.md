---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Ciao! Sono Betty Tealdo.
      color: text-dark
    subtitle: Venditrice presso Alimenti Superiori
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: 'Prodotti più venduti:'
      color: text-dark
      styles:
        self:
          textAlign: left
    items:
      - type: FeaturedItem
        title: Moringa Oleifera
        subtitle: 12€ - 20€
        image:
          type: ImageBlock
          url: /images/376-9d1-MORINGA-OLEIFERA-IN-POLVERE-600x600.jpg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions:
          - type: Button
            label: Get started
            altText: ''
            url: /moringa
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
        tagline: Integratore
      - type: FeaturedItem
        title: Maca Nera
        subtitle: 12€ - 20€
        image:
          type: ImageBlock
          url: /images/371-4b5-MACA-NERA-IN-POLVERE-600x600.jpg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        tagline: Energizzante
      - type: FeaturedItem
        title: Zenzero in polvere
        subtitle: 5€ - 10€
        image:
          type: ImageBlock
          url: /images/326-bc8-ZENZERO-MACINATO-600x600.jpg
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        tagline: Spezia
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: flex-start
      subtitle:
        textAlign: center
  - title:
      text: Contattami!
      color: text-dark
      type: TitleBlock
    subtitle: >-
      Se hai domande, richieste specifiche o hai bisogno di consigli sui nostri
      prodotti, sono qui per aiutarti!
    text: ''
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
      label: ''
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
    actions:
      - type: Link
        label: Facebook
        altText: Facebook
        url: /facebook
        showIcon: true
        icon: facebook
        iconPosition: left
        style: secondary
        elementId: ''
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
