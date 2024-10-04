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
        street: 解放大路2519号
        city: 长春
        region: 吉林
        postcode: '130012'
        country: 中国
        country_code: CN
      coordinates:
        latitude: '125.32'
        longitude: '43.88'
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
