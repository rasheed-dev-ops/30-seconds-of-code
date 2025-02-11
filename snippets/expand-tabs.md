---
title: Expand tabs into spaces
type: snippet
tags: [string,regexp]
author: chalarangelo
cover: houses-rock-sea
dateModified: 2020-09-15T16:28:04+03:00
---

Convert tabs to spaces, where each tab corresponds to `count` spaces.

- Use `String.prototype.replace()` with a regular expression and `String.prototype.repeat()` to replace each tab character with `count` spaces.

```js
const expandTabs = (str, count) => str.replace(/\t/g, ' '.repeat(count));
```

```js
expandTabs('\t\tlorem', 3); // '      lorem'
```
