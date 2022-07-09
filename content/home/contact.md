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
    provider: formspree
    formspree:
      id: mzbkqjak
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: abbaselmas@gmail.com
  phone: +905432558823
  address:
    street: Çukurova University Computer Engineering Department Building Room 111
    city: Adana
    region: 
    postcode: '01180'
    country: Turkey
    country_code: TR
  coordinates:
    latitude: '37.06103'
    longitude: '35.35068'
  directions:
  office_hours:
    - 'Weekdays 08:30 to 09:30'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/aabbstr'
    - icon: telegram
      icon_pack: fab
      name: Telegram
      link: 'https://telegram.me/@abbaselmas'

design:
  columns: '2'
---
