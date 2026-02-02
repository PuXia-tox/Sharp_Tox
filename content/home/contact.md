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
  email: p.xia@bham.ac.uk
  address:
    street: School of Biosciences, University of Birmingham, Edgbaston
    city: Birmingham
    region: UK
    postcode: B15 2TT
    country: United Kingdom
  directions: Enter Building take the stairs/elevators to Office 304 on Floor 3

design:
  columns: '2'
---
