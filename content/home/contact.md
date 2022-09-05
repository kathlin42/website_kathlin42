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
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building Allmandring 35 and take the right Floor to Office 200
  office_hours:
    - 'via an appointment'
  appointment_url: 'https://calendly.com'
design:
  columns: '2'
---
