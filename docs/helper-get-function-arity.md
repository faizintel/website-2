---
id: babel-helper-get-function-arity
title: @babel/helper-get-function-arity
sidebar_label: babel-helper-get-function-arity
---


## Usage

```javascript
import getFunctionArity from "@babel/helper-get-function-arity";

function wrap(state, method, id, scope) {
  // ...
  if (!t.isFunction(method)) {
    return false;
  }

  const argumentsLength = getFunctionArity(method);

  // ...
}
```

