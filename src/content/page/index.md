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

      ### ⬇️ [Download beta 0.3.0](https://github.com/mortendk/saga11/archive/refs/tags/v.0.3.0-beta.zip)

      1. install saga


      ```shell

      $ npm install

      ```


      2. Spin it up:


      ```shell

      $ npm  start

      ```

      The site is ready for local development on port 3791

      👩‍💻 localhost:3791

      ### ✍️ Admin interface

      To make the admin work clone the env.example to .env
      (else the system dont know where the admin is)


      👉 localhost:3791/admin

      ⌨️ Keyboard shortcut  cmd + shift + e

      ### 💅 Themes

      Themes are in /src/themes/...

      The are configured in /saga11.config.js

      ### 📜 Content

      Content is in "/src/content/"


      3. Create the PWA statupscreen


      ```shell

      $ npm run splash-screens:build

      ```

      ## 🚚 Build to Production

      4. Now The site is ready to be published, build it and send it to the internet!

      ```shell

      $ npm build

      ```


      5. Cleanup the build folder - just to remove the clutter


      ```shell

      $ npm run cleanup

      ```

      🎈 Saga11 is build on top of [11ty](https://11ty.dev) & [NetlifyCMS](https://www.netlifycms.org/)


      🪲 Bugs & comments [github](https://github.com/mortendk/saga11)
  - type: features
    template: components/feature/feature.njk
    title: "11 Reasons "
    feature:
      - title: Templates is king!
        text: >
          The templates are in complete control over the output. Content
          types & components have each seperate template files for über customization.
        icon: icons/paint-brush.svg
      - title: "Content types & Components "
        text: Pages, stories & noticiation content types + pagebuilding with html components.
        icon: icons/adjustments-horizontal.svg
      - title: Static Web + CMS  = Awesome
        text: Use Netflifycms to edit the content or use the texteditor for extra nerd points.
        icon: icons/heart.svg
      - title: 4 Hundo!
        text: Make the web awesome - Lighthouse scores in the 100/100/100/100 range.
        icon: icons/cake.svg
      - title: Fast
        text: Its a Static websites it cant get faster than that! Its Minified Compressed and
          stamped on twice.
        icon: icons/bolt.svg
      - title: "NO database "
        text: >
          All data & Content is in markdown or json. No fiddeling with database
          connectors.
        icon: icons/table-cells.svg
      - title: "KISS "
        text: Build on the nordic design principles of keeping things simple and removing the clutter.
        icon: icons/rss.svg
      - title: Calendars
        text: Add pages to your Calendar as the page is an event - no more facebook events ;)
        icon: icons/calendar.svg
      - title: Open Graph & RSS
        text: Sharing is caring custom preview for all social media & offcourse RSS (and sitemaps, humans and robots.txt)
        icon: icons/share.svg
      - title: Its all there
        text: Everything lives in the repo
        icon: icons/folder.svg
      - title: PWA build in
        icon: icons/device-phone-mobile.svg
        text: HTML > Apps !
    text: ""
url: /
eleventyNavigation:
  key: main
  title: Home
  order: 0
layout: page/frontpage.njk
eleventyExcludeFromCollections: false
---

👋 Hi world!

## Markdown + HTML + CSS = 💜

**Saga11** is a static website builder for webdesigners that dreams of:

1. Complete über control of HTML, CSS & JS.
2. ~~The complexety of "modern" web.~~
3. CMS for editing but witout a database
