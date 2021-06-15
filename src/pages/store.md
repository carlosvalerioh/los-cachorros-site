---
title: Store
sections:
- type: store_section
  template: store_section
  section_id: store_section
- type: featured_products_section
  template: featured_products_section
  title: MÁS VENDIDO
  section_id: featured_products_section
  icon: true
  featured_products:
  - src/pages/products/pro-plan-adulto-raza-mediana-13-kg.md
  - src/pages/products/nupec-adulto-20-kgs.md
- type: promotion_section
  template: promotion_section
  section_id: promotion_section
  title: Conoce todas nuestras ubicaciones
  subtitle: 10 tiendas en la CDMX
  image: "/images/brooke-cagle-eycex1e9eiy-unsplash.jpg"
  background_image: "/images/noun_Dog_3587160-6.png"
  cta:
    type: action
    template: action
    title: UBICACIONES
    url: "/ubicaciones"
    style: primary
    arrow: true
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: Store
  description: This is the store page
  extra:
  - name: og:type
    value: website
    keyName: property
  - name: og:title
    value: Store
    keyName: property
  - name: og:description
    value: This is the store page
    keyName: property
  - name: og:image
    value: images/header.jpg
    keyName: property
    relativeUrl: true
  - name: twitter:card
    value: summary_large_image
  - name: twitter:title
    value: Store
  - name: twitter:description
    value: This is the store page
  - name: twitter:image
    value: images/header.jpg
    relativeUrl: true
template: store

---
