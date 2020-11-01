```
var ary = [0,1,2];
ary[10] = 10;
console.log(ary);
console.log(ary.filter(function(x) { return x === undefined;}));
console.log(ary.filter(function(x) { return x !== undefined;}));
```

```
[0,1,2,null,null,null,null,null,null,null,10]
[]
[0,1,2,10]
```

