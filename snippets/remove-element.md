---
title: Remove DOM element
type: snippet
tags: [browser]
author: chalarangelo
cover: by-the-lighthouse
dateModified: 2021-01-07T00:20:34+02:00
---

Removes an element from the DOM.

- Use `Node.parentNode` to get the given element's parent node.
- Use `Node.removeChild()` to remove the given element from its parent node.

```js
const removeElement = el => el.parentNode.removeChild(el);
```

```js
removeElement(document.querySelector('#my-element'));
// Removes #my-element from the DOM
```
