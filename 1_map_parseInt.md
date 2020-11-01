```
Q. What is the result of this expression? (or multiple ones)
          
["1", "2", "3"].map(parseInt)
```
A.
https://stackoverflow.com/questions/22036300/what-is-1-2-3-mapparseint-result

If the radix value is not of the Number type it will be coerced to a Number.

If radix is undefined or 0, it is assumed to be 10 except when the number begins with the character pairs 0x or 0X, in which case a radix of 16 is assumed.

If the radix is smaller than 2 or bigger than 36, the return value is NaN.

If the first character cannot be converted to a number with the radix in use, parseInt returns NaN. For example, 3 is not binary.
