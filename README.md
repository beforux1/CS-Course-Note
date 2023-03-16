# [Javascript-Full-Course-Note](https://www.youtube.com/watch?v=8dWL3wF_OMw&t=23220s)

1. While and do while 
- [do...while](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while)
- [while](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)


2. Ternary operator
```js
Condition? exprIfTrue: exprIfFalse
```
- Example:
```js
Function checkWinner(win){
    win ? console.log("You win"):console.log("You lose")
}
checkWinner(true)
```

checkWinner(true)

3. Template literals `
4. Const / var / let 
- [Difference Between Var, Let and Const in ES6](https://medium.com/infancyit/difference-between-var-let-and-const-in-es6-16a08d74b8b2)
5. Spread operator …[array] > to individual character
6. Rest parameter
7. Callback > important functions
8. array.reduce()
9. Sorting  
```js
function descendSort(a,b) { return a-b}
```
```js
Arr.sort((a,b) => a-b)
```
10.Function expression
11.Nested functions
12.Map 
[Map() constructor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map/Map)

13. Object = a group of properties and methods
- Properties = what an object has
- Methods = what an object can do 
- Use . to access properties/methods

14. Class = a blueprint for creating objects to  define what properties and methods they have use a constructor for unique properties.
15. constructor = a special method of a class, accepts arguments and assigns properties
16. Static  = belongs to the class, not the objects. 
17. Inheritance 
18. Super
19. Get and set
- Get = binds an object property to a function when that property is accessed 
- [Property getters and setters](https://javascript.info/property-accessors)
20.
```js
Try{} catch(error){}
```

21.Throw 

22.Finally 

23.setTimeout() / clearTimeout()

24.Promise = “I promise to return something in the future “.*Important*

25.Async = makes a function to return a Promise

26. Await = make an async function wait for a Promise ( await can only be used in the async function.)

27. ES6 Modules

28. DOM = Document Object Model (API) An interface for changing the content of a page
Events

29. addEventListener(event, function, useCapture)

30. canvasAPI

31. Window 
```js
console.dir()
```

32.
Cookies = a small text file stored on your computer used to remember information about the users saved in name=value pairs 
