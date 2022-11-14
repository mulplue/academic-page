---
<script src="https://kit.fontawesome.com/a97ee919b1.js" crossorigin="anonymous"></script>
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
  email: mulplue@outlook.com
  phone: +86-183-5707-5089
  address:
    street: 38 Zheda Road
    city: Hangzhou
    region: Xihu District
    postcode: '310007'
    country: China
    country_code: CHN
  coordinates:
    latitude: '30.1540'
    longitude: '120.0730'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 9:00 to :00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: <i class="fa-brands fa-linkedin"></i>
      # icon_pack: fab
      name: mulplue
      link: 'https://twitter.com/mulplue'
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  columns: '2'
---
