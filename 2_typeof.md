```
What is the result of this expression? (or multiple ones)

          
[typeof null, null instanceof Object]
```
https://stackoverflow.com/questions/28956060/javascript-confusing-syntax-inconsistence-for-null-instanceof-and-typeof

typeof will always return "object" for native non callable objects.

However, null is a reference.

