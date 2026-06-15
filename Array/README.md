# Array Questions

## Q9 - Count Numbers Greater Than 50

```js
function countGreaterThan50(arr) {
  let count = 0;

  for (let num of arr) {
    if (num > 50) {
      count++;
    }
  }

  return count;
}
```

## Q10 - Get Even Numbers

```js
function getEvenNumbers(arr) {
  let result = [];

  for (let num of arr) {
    if (num % 2 === 0) {
      result.push(num);
    }
  }

  return result;
}
```
## Q28 - Sum of Numbers Greater Than 20

```js
function sumGreaterThan20(arr) {
  let sum = 0;

  for (let data of arr) {
    if (data > 20) {
      sum += data;
    }
  }

  return sum;
}
```
