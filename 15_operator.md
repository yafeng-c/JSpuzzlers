https://masteringjs.io/tutorials/fundamentals/compare-arrays#:~:text=Arrays%20are%20objects%20in%20JavaScript,arrays%20are%20the%20same%20reference
```
var a = [1, 2, 3],
    b = [1, 2, 3],
    c = [1, 2, 4]
a ==  b
a === b
a >   c
a <   c
```
Arrays are compared lexicographically with > and <, but not with == and ===
