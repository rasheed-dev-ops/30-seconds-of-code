---
title: Head of array
type: snippet
tags: [array]
cover: clay-pot-horizon
dateModified: 2020-10-19T22:49:51+03:00
---

Returns the head of an array.

- Check if `arr` is truthy and has a `length` property.
- Use `arr[0]` if possible to return the first element, otherwise return `undefined`.

```js
const head = arr => (arr && arr.length ? arr[0] : undefined);
```

```js
head([1, 2, 3]); // 1
head([]); // undefined
head(null); // undefined
head(undefined); // undefined
```
