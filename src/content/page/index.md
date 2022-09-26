---
title: Saga11
image: /upload/facebook.jpg
card:
  title: Saga11 Static Websites FTW
  text: |-
    Saga11 is a static website generator build on the shoulders of 11ty
    Build for webdesigners & others with an unhealthy obsession of markup
components:
  - type: text
    template: components/text/text.njk
    title: saga11
    text: >-
      
      ## Quick start

      1. install saga


      ```shell

      $ npm install

      ```


      2. Spin it up:


      ```shell

      $ npm  start

      ```


      ### ✍️ Admin interface

      To make the admin work clone the env.example to .env

      (else the system dont know where the admin is)


      👉 Go to the [admin interface admin](/admin)

      ⌨️ Keyboard shortcut  cmd + shift + e

      ### 💅 Themes

      Themes are in /src/themes/

      The are configured in /saga11.config.js

      ### 📜 Content

      Content is in "/src/content/"



      3. Create the PWA statupscreen


      ```shell

      $ npm run splash-screens:build

      ```


      4. Cleanup the build folder


      ```shell

      $ npm run cleanup

      ```

      🎈 Saga11 is build on top of [11ty](https://11ty.dev) & [NetlifyCMS](https://netlifycms.com)


      🪲 Bugs & comments [github](https://github.com/mortendk/saga11)
  - type: features
    template: components/feature/feature.njk
    title: "11 Reasons "
    feature:
      - title: Templates is king
        text: >
          The templates are in complete control over the output, every content
          type & component have seperate template files.
        icon: icons/paint-brush.svg
      - title: "Content types & Components "
        text: Predefined content types with html componenets for pagebuilding
        icon: icons/adjustments-horizontal.svg
      - title: Static Web + CMS  = Awesome
        text: Netflifycms is configures to control the content types and compomenets
          Best of both worlds
        icon: icons/heart.svg
      - title: 4 Hundo
        text: Build the web right and get the 100/100/100/100 on lighthouse
        icon: icons/cake.svg
      - title: Fast
        text: Its a Static websites cant get faster than that, minified compressed and
          stamped on
        icon: icons/bolt.svg
      - title: "NO database "
        text: >
          All data & Content is in markdown or json. No fiddeling with database
          connectors
        icon: icons/table-cells.svg
      - title: "RSS "
        text: Share with the world RSS never left its still rocking
        icon: icons/rss.svg
      - title: Calendars
        text: Add pages to calendar as the page is an event
        icon: icons/calendar.svg
      - title: Open Graph
        text: Sharing is caring custom preview for all social media
        icon: icons/share.svg
      - title: Its all there
        text: Everything is in the github repo - No secret magic just html, css and some
          markdown
        icon: icons/folder.svg
      - title: PWA build in
        icon: icons/device-phone-mobile.svg
        text: HTML > Apps ;)
    text: ""
url: /
eleventyNavigation:
  key: main
  title: Home
  order: 0
layout: page/frontpage.njk
eleventyExcludeFromCollections: false
---

## Hello World 👋

Saga11 is a static website builder made for webdesigners that wants complete control of the end markup without any overhead or complex systems to battle with. 💜

Theres a cms in the backend if you dont want to fiddle with the markdown files.

🤌 Github [G﻿ithub repo](https://github.com/mortendk/saga11)
