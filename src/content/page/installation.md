---
title: Installation
url: installation
eleventyNavigation:
  parent: main
  title: Installation
  key: installation
layout: page/page.njk
eleventyExcludeFromCollections: false
---

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
