---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Feel free to reach me.

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
      captcha: true

  # Contact details (edit or remove options as required)
  email: masum35-357@diu.edu.bd
  phone: +8801743819848
  address:
    street: Ashulia, Savar
    city: Dhaka
    country: Bangladesh
    country_code: BD
  appointment_url: 'https://calendly.com/masum_akando'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/masum_akando'
    
    

design:
  columns: '2'
---
