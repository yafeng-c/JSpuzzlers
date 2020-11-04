```
function showCase(value) {
    switch(value) {
    case 'A':
        console.log('Case A');
        break;
    case 'B':
        console.log('Case B');
        break;
    case undefined:
        console.log('undefined');
        break;
    default:
        console.log('Do not know!');
    }
}

showCase(new String('A'));
showCase("A");
```
A switch statement first evaluates its expression. It then looks for the first case clause whose expression evaluates to the same value as the result of the input expression (using the strict comparison, ===) 

console.log(typeof new String('A'));

console.log(typeof 'A');
