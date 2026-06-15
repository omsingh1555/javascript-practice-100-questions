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
## Q11 - First Even Number

```js
function firstEven(arr) {
  for (let num of arr) {
    if (num % 2 === 0) {
      return num;
    }
  }
  return null;
}
```

## Q12 - Largest Number

```js
function largestNumber(arr) {
  let largest = arr[0];

  for (let num of arr) {
    if (num > largest) {
      largest = num;
    }
  }

  return largest;
}
```

## Q13 - Smallest Number

```js
function smallestNumber(arr) {
  let smallest = arr[0];

  for (let num of arr) {
    if (num < smallest) {
      smallest = num;
    }
  }

  return smallest;
}
```

## Q14 - Sum Even Numbers

```js
function sumEvenNumbers(arr) {
  let sum = 0;

  for (let num of arr) {
    if (num % 2 === 0) {
      sum += num;
    }
  }

  return sum;
}
```

## Q15 - Count Odd Numbers

```js
function countOddNumbers(arr) {
  let count = 0;

  for (let num of arr) {
    if (num % 2 !== 0) {
      count++;
    }
  }

  return count;
}
```

## Q16 - First Odd Number

```js
function firstOdd(arr) {
  for (let num of arr) {
    if (num % 2 !== 0) {
      return num;
    }
  }

  return null;
}
```

## Q17 - Last Element

```js
function lastElement(arr) {
  if (arr.length > 0) {
    return arr[arr.length - 1];
  }

  return null;
}
```

## Q18 - Second Element

```js
function secondElement(arr) {
  if (arr.length >= 2) {
    return arr[1];
  }

  return null;
}
```

## Q19 - Contains Value

```js
function containsValue(arr, value) {
  for (let num of arr) {
    if (num === value) {
      return true;
    }
  }

  return false;
}
```

## Q20 - Count Five

```js
function countFive(arr) {
  let count = 0;

  for (let num of arr) {
    if (num === 5) {
      count++;
    }
  }

  return count;
}
```

## Q21 - Count Occurrences

```js
function countOccurrences(arr, value) {
  let count = 0;

  for (let num of arr) {
    if (num === value) {
      count++;
    }
  }

  return count;
}
```

## Q22 - All Positive

```js
function allPositive(arr) {
  for (let num of arr) {
    if (num <= 0) {
      return false;
    }
  }

  return true;
}
```

## Q23 - All Even

```js
function allEven(arr) {
  for (let num of arr) {
    if (num % 2 !== 0) {
      return false;
    }
  }

  return true;
}
```

## Q24 - Has Even

```js
function hasEven(arr) {
  for (let num of arr) {
    if (num % 2 === 0) {
      return true;
    }
  }

  return false;
}
```

## Q25 - Count Even Greater Than 10

```js
function countEvenGreaterThan10(arr) {
  let count = 0;

  for (let num of arr) {
    if (num > 10 && num % 2 === 0) {
      count++;
    }
  }

  return count;
}
```

## Q26 - Get Even Greater Than 10

```js
function getEvenGreaterThan10(arr) {
  let result = [];

  for (let num of arr) {
    if (num > 10 && num % 2 === 0) {
      result.push(num);
    }
  }

  return result;
}
```

## Q27 - Numbers Greater Than 20

```js
function greaterThan20(arr, num) {
  let newArray = [];

  for (let data of arr) {
    if (data > num) {
      newArray.push(data);
    }
  }

  return newArray;
}
```

## Q28 - Sum Greater Than 20

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
