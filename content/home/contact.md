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
    address:
     street: 700 University Avenue
     city: Toronto
     region: ON
   # postcode: 'M5G1X6'
     country: Canada
     country_code: CA
   coordinates:
    latitude: '46.658891'
    longitude: '-79.390513'
    directions: 9 floor desk 9145 3
 
  columns: '2'
---
