---
title: "Chessboard Pattern"
description: "Solution to the chessboard problem from Eloquent JavaScript"
---

# Chessboard Pattern

This article explains how to generate an 8×8 chessboard with a nested loop.

## Code Snippet

```js
function chessboard(size = 8) {
  let result = "";
  for (let y = 0; y < size; y++) {
    for (let x = 0; x < size; x++) {
      result += (x + y) % 2 === 0 ? " " : "#";
    }
    result += "\n";
  }
  return result;
}

