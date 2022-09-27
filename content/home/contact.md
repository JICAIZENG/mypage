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
  email: jicai@airzona.edu
  #phone: 
  address:
    street: 1133 James E. Rogers Way
    city: Tucson
    region: AZ
    postcode: '85719'
    country: United States
    country_code: US
  coordinates:
    latitude: '32.233409'
    longitude: '-110.953626'
  directions: JWH
  office_hours:
    - 'Mon-Fri 8AM to 5:30PM'
    - 'Sat-Sun 10AM to 5PM'
  appointment_url: 'https://calendly.com/jicai/30min'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://mobile.twitter.com/jicaizeng'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://arizona.zoom.us/j/83457102690'

design:
  columns: '2'
---
