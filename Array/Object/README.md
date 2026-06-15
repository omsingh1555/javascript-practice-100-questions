# Object Questions

## Q1 - Check if Object has Age Property

```js
function hasAge(obj) {
  for (let key in obj) {
    if (key === "age") {
      return true;
    }
  }
  return false;
}
```

## Q2 - Sum All Object Values

```js
function sumValues(obj) {
  let sum = 0;

  for (let key in obj) {
    sum += obj[key];
  }

  return sum;
}
```
