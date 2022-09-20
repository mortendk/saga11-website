---
title: Saga11
image: ""
card:
  title: Saga11 Static Websites FTW
  text: |-
    Saga11 is a static website generator build on the shoulders of 11ty
    Build for webdesigners & others with an unhealthy obsession of markup
components:
  - type: text
    template: components/text/text.njk
    title: saga11
    text: >
      Saga eleven - A Static Website builder powered by 11ty and netlifycms


      Requirements: node + github + some knowledge of 11ty


      ## ⚠️Super duper alpa version 0.2


      Fair warning this is still in alpha ;)


      ## Quick start


      1. install saga


      ```

      $ npm install

      ```


      2. Spin it up:


      ```

      $ npm  start

      ```


      👉 To make the admin work clone the env.example to .env

      (else the system dont know where the admin is)


      🤖 go to the [admin interface admin](/admin)


      💅 Themes are in /src/themes/

      The are configured in /saga11.config.js


      📜 content is in /src/content/


      🎈 saga11 is build on top of [11ty](https://11ty.dev) & [NetlifyCMS](https://netlifycms.com)


      🪲 bugs & comments [github](https://github.com/mortendk/saga11)


      📲 PWA statupscreen


      ```

      $ npm run splash-screens:build

      ```


      🗑 Cleanup the build folder


      ```

      $ npm run cleanup

      ```
  - type: features
    template: components/feature/feature.njk
    title: "11 Reasons "
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
