---
white_header: true
sections:
  - type: hero_section
    template: hero_section
    section_id: hero_section
    background_image: /images/karsten-winegeart-tIWBJN8t7zE-unsplash.jpg
    background_image_opacity: 65
    content: >
      # Los Cachorros


      Todas las marcas de alimentos y alimentos premium para tus mascotas a los
      mejores precios.
    actions:
      - type: action
        template: action
        title: CATÁLOGO
        url: /store
        style: primary
        arrow: true
  - type: featured_products_section
    template: featured_products_section
    title: MÁS VENDIDO
    section_id: best_sellers_section
    light_title: true
    icon: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: testimonials_section
    template: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
        author:
          name: John Dope
          location: 'Colorado, USA'
      - text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
        author:
          name: Major Payne
          location: 'VA, USA'
  - section_id: lorem-ipsum
    title: lorem-ipsum
    subtitle: lorem-ipsum
    cta:
      title: lorem-ipsum
      url: '#'
      style: primary
      arrow: false
      type: action
    type: promotion_section
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
template: home
---
