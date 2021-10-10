## 1
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


## 2
```js
function function1() {
    console.log('Welcome to My Console,');
}

function function2() {
    console.log('Blah blah blah blah extra-blah');
}

function1();

setTimeout(function2, 3000);
```


## 3
```js
setTimeout(function(){ 
    console.log("Ready")
}, 1000);
```
