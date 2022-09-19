---
title: content
card:
  title: "build content "
url: content
eleventyNavigation:
  parent: main
  title: content
layout: page/page.njk
eleventyExcludeFromCollections: false
---
H﻿ow the contet model works 

```haml
---
title: the most amazing thing
layout: base.njk
date: Last Modified # 2018-01-01
permalink: foo/bar/baz/
eleventyNavigation:
  key: main
  title: Home
  order: 0

eleventyExcludeFromCollections: false

pagination:
  data: testdata
  size: 2

testdata:
 - item1
 - item2
 - item3
 - item4

tags:
  - cat
  - dog
---

content
```