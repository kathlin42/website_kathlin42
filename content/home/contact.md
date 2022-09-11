---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: katharina.lingelbach@mailbox.org
  phone: +49 711 970 5342
  address:
    street: Nobelstraße 12
    city: Stuttgart
    postcode: '70569'
    country: Germany
  coordinates:
    latitude: '48.74025681016322'
    longitude: '9.09608411155283'
  directions: Building IAT University of Stuttgart, Allmandring 35, Ground Floor, Right Wing, Office 0.134
design:
  columns: '2'
---
