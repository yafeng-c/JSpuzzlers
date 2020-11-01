```
var val = 'smtg';
console.log('Value is ' + (val === 'smtg') ? 'Something' : 'Nothing');
```

the + operator has higher precedence than the ternary (conditional) one.

So, it equals

console.log('Value is true' ? 'Something' : 'Nothing');
