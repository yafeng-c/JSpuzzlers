```
What is the result of this expression? (or multiple ones)
          
var name = 'World!';
(function () {
    if (typeof name === 'undefined') {
        var name = 'Jack';
        console.log('Goodbye ' + name);
    } else {
        console.log('Hello ' + name);
    }
})();

```
https://stackoverflow.com/questions/22780398/few-confuse-about-variable-scope-of-anyonmous-function-in-javascript

it equals to
```
var name = 'World!';
(function () {
    var name;
    if (typeof name === 'undefined') {
        name = 'Jack';
        console.log('Goodbye ' + name);
    } else {
        console.log('Hello ' + name);
    }
})();
```
