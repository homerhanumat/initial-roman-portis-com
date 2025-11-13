---
title: "Reversing an Array"
description: "Solution to the reversing array problem from Eloquent JavaScript"
---

# Reversing an Array

This article explains the **reverseArray** and **reverseArrayInPlace** functions.

## Code Snippet

```js
function reverseArray(arr) {
  let out = [];
  for (let i = arr.length - 1; i >= 0; i--) {
    out.push(arr[i]);
  }
  return out;
}

function reverseArrayInPlace(arr) {
  for (let left = 0, right = arr.length - 1; left < right; left++, right--) {
    let temp = arr[left];
    arr[left] = arr[right];
    arr[right] = temp;
  }
  return arr;
}
