# String Questions

## Q1 - Reverse a String

```js
function reverseString(str) {
  let reversed = "";

  for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
  }

  return reversed;
}
```

## Q2 - Check Palindrome

```js
function isPalindrome(str) {
  let reversed = "";

  for (let i = str.length - 1; i >= 0; i--) {
    reversed += str[i];
  }

  return str === reversed;
}
```

## Q3 - Count Characters

```js
function countCharacters(str) {
  return str.length;
}
```

## Q4 - Convert to Uppercase

```js
function toUpper(str) {
  return str.toUpperCase();
}
```

## Q5 - Convert to Lowercase

```js
function toLower(str) {
  return str.toLowerCase();
}
```
