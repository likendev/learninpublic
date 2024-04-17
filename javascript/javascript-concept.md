# Javascript Concept

## === vs ==
- type sensitive
- ```javascript 
    null == undefined; // true 
    null === undefined; // false
  ```
## toString()
- Number / BigInt `toString()` methods take an optional `radix` params
- E.g. Number.toString(2) convert the number to base 2 string
- [References](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString#parameters)

## Falsey value
- `false`, `null`, `undefined`, `0`, `-0`, `NaN` and `''` (empty string)
- Apply !! to check if it's falsey or truthy
