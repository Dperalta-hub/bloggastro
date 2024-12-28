---
title: Blog de Salud Digestiva
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: BLOG DE SALUD DIGESTIVA
      color: text-primary
    subtitle: Dr Peralta Daniel
    text: >
      Un lugar informativo, de prevencion y un canal de comunicacion para el
      publico en general.
    actions: []
    media:
      type: ImageBlock
      url: /images/_cf006d48-cfe0-431d-9cfb-0f5af3dac259.jpg
      altText: Fun feature preview
      styles:
        self:
          padding:
            - pt-1
            - pb-12
            - pl-24
            - pr-20
          margin:
            - mt-20
            - mb-20
            - mr-20
            - ml-20
          borderColor: border-neutralAlt
          borderStyle: solid
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: FeaturedItemsSection
    title:
      text: Key Benefits
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: ''
        subtitle: Como mantener un sistema digestivo saludable.
        text: >+
          ###


          1.  **Dieta equilibrada:** Rica en frutas, verduras, granos integrales
          y alimentos fermentados.


          2.  **Ingerir suficiente agua:** Ayuda a mantener las heces suaves y a
          prevenir el estreñimiento.


          3.  **Ejercicio regularmente:** Mejora el peristaltismo intestinal.


          4.  **Evitar el exceso de alcohol y alimentos ultraprocesados.**


          5.  **Masticar  bien los alimentos:** Facilita el trabajo del estómago
          e intestinos.


          6.  **Consultar  a un médico si tienes síntomas persistentes:** Como
          acidez, dolor abdominal o cambios en el hábito intestinal.

        actions: []
        elementId: null
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: ''
        subtitle: ''
        text: >+
          El sistema digestivo es un engranaje complejo pero bien coordinado que
          nos permite obtener energía y nutrientes esenciales. Comprender su
          funcionamiento no solo nos ayuda a cuidar nuestra salud, sino también
          a identificar posibles problemas antes de que se vuelvan graves. Si
          tienes dudas o inquietudes sobre tu sistema digestivo, este es el
          espacio para compartirlas y encontrar respuestas.



        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: This is a badge
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
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
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
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
        label: Submit
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
