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
  # email: test@example.org
  # phone: 888 888 88 88
   address:
     street: 700 University Avenue
     city: Toronto
     region: CA
     postcode: 'M5G 1X6'
     country: Canada
     country_code: CA
  coordinates:
    latitude: '46.658891'
    longitude: '-79.390513'
  directions: 9 floor, desk 9145-3
  # office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
  #  - icon: twitter
  #    icon_pack: fab
  #    name: DM Me
  #    link: 'https://twitter.com/Twitter'
  #  - icon: video
  #    icon_pack: fas
  #    name: Zoom Me
  #    link: 'https://zoom.com'

design:
  columns: '2'
---
