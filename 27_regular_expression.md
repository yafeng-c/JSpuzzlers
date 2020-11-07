```
What is the result of this expression? (or multiple ones)
          
var a = /123/,
    b = /123/;
a == b
a === b
```

"==" and "===" compares two objects based on memory reference,
so the "==" operator will return true only if the two object references it is comparing represent exactly same object,
otherwise "==" will return false.

While, in JavaScript, regular expressions are objects.  regular expressions are patterns used to match character combinations in strings. Two regular expressions are not indentical to each other even when their contents are the same.
