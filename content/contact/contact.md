---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: CONTACT
subtitle:

content:
  # Contact (edit or remove options as required)

 # email: test@example.org
 # phone: 888 888 88 88
  address:
    street: Rued Langgaards Vej 7
    city: Copenhagen
#    region: CA
    postcode: '2300'
    country: Denmark
    country_code: DK
  coordinates:
    latitude: '55.659284123843186'
    longitude: '12.590917184001094'
  directions: Located in the DR Building section of ITU
 # office_hours:
 #   - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://buttondown.email/DigitalPlayITU'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---
