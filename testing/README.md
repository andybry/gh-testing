```ts
// @errors: 2339
let x: [string, number];
x = ["hello", 10]; // OK
/// ---cut---
console.log(x[0].substring(1));
console.log(x[1].substring(1));
```