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
# Object Questions

## Q34 - Count Number Values

```js
function countNumbers(obj) {
  let count = 0;

  for (let key in obj) {
    if (typeof obj[key] === "number") {
      count++;
    }
  }

  return count;
}
```

## Q35 - Count String Values

```js
function countStrings(obj) {
  let count = 0;

  for (let key in obj) {
    if (typeof obj[key] === "string") {
      count++;
    }
  }

  return count;
}
```

## Q36 - Get Number Values

```js
function getNumberValues(obj) {
  let result = [];

  for (let key in obj) {
    if (typeof obj[key] === "number") {
      result.push(obj[key]);
    }
  }

  return result;
}
```

## Q37 - Get String Values

```js
function getStringValues(obj) {
  let result = [];

  for (let key in obj) {
    if (typeof obj[key] === "string") {
      result.push(obj[key]);
    }
  }

  return result;
}
```

## Q38 - Has Number Value

```js
function hasNumberValue(obj) {
  for (let key in obj) {
    if (typeof obj[key] === "number") {
      return true;
    }
  }

  return false;
}
```

## Q39 - Has String Value

```js
function hasStringValue(obj) {
  for (let key in obj) {
    if (typeof obj[key] === "string") {
      return true;
    }
  }

  return false;
}
```

## Q40 - Sum Number Values

```js
function sumNumberValues(obj) {
  let sum = 0;

  for (let key in obj) {
    if (typeof obj[key] === "number") {
      sum += obj[key];
    }
  }

  return sum;
}
```

## Q41 - Largest Number Value

```js
function largestNumberValue(obj) {
  let largest = -Infinity;

  for (let key in obj) {
    if (
      typeof obj[key] === "number" &&
      obj[key] > largest
    ) {
      largest = obj[key];
    }
  }

  return largest;
}
```
