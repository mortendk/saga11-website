---
title: Saga11
image: ""
components:
  - type: text
    template: components/text/text.njk
    text: |
      
      ## Quick start

      1. install saga

      ```
      $ npm install
      ```

      2. Spin it up:

      ```
      $ npm  start
      ```

      http://localhost:3791

      3. build the production site

      ```
      npm build
      ```

      ## Notes

      ### local envirotment

      set up an .env file for production copy the env.example to .env

      ### Change theme

      open saga11.config.js and change the theme

      modify the scripts for your need in package.json

      ### Build startscreens for PWA

      ```
      $ npm run splash-screens:build
      ```

      ### Cleanup the build folder

      ```
      $ npm run cleanup
      ```
  - type: features
    template: components/feature/feature.njk
    title: "11 awesome "
    feature:
      - title: Themes in control
        text: |-
          The templates is controlling everything
          e﻿ach component have templates
      - title: NO database
        text: |-
          L﻿ike really really fast and unbreakable 

          Static websites ftw :) 
      - title: "Design Components "
        text: "Build with the power of NetlifyCMS the editing experience can be done
          through the browser instad of a text editor "
      - title: Static Web + CMS  = Awesome
        text: "Control your static website fron the browse "
      - title: Fast & Secure
        text: |-
          L﻿ike really really fast.
          Static websites ftw :) 
      - title: "RSS "
        text: S﻿hare your website with the world with the amazing RSS feeds
      - title: 100/100/100/100/100
        text: B﻿uild the web right
      - title: Calendars
        text: A﻿dd you page to your calendar - perfect for event sites
      - title: Open Graph
        text: S﻿haring is caring
      - title: PWA build in
        text: Cause we can
      - title: 101% HTML control
        text: The system provides only variables that the theme then rocks
    text: "Eleven things "
url: /
eleventyNavigation:
  key: main
  title: Home
  order: 0
layout: page/frontpage.njk
eleventyExcludeFromCollections: false
---
