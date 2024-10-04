---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        联系我们。
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 450 Serra Mall
        city: 长春
        region: 吉林
        postcode: '94305'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
    
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
