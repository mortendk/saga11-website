---
title: content
card:
  title: content model
url: content
eleventyNavigation:
  parent: main
  title: Content model
  order: 10
layout: page/page.njk
eleventyExcludeFromCollections: true
---

Markdown is used for content with frontmatter for data

### page.md:

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
