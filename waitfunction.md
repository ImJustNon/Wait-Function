```js
function wait(milliseconds) {
  const date = Date.now();
  let currentDate = null;
  do {
    currentDate = Date.now();
  } while (currentDate - date < milliseconds);
}

console.log("start !!");
wait(2000);
console.log("go");
```
