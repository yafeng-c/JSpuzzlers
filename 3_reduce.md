```
What is the result of this expression? (or multiple ones)
          
[ [3,2,1].reduce(Math.pow), [].reduce(Math.pow) ]
```

arr.reduce(callback( accumulator, currentValue[, index[, array]] ) {
  // return result from executing something for accumulator or currentValue
}[, initialValue]);

an empty array without an initialValue will throw a TypeError

Math.pow(3, 2)    // 9
Math.pow(9, 1)    // 9



A value to use as the first argument to the first call of the callback. If no initialValue is supplied, the first element in the array will be used as the initial accumulator value and skipped as currentValue.

