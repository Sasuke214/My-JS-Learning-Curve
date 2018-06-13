# My-JS-Learning-Curve
I put every points that i encounter while learning js, its kinda like notes i generally make while learning new stuffs


## JS ES6

### LET

syntax: 
  ```javascript
  let var_name;
  let var_name1,...,var_namen;
  let var_name = value1;
  
  ```
  
	
*1. It's Scope is only within the block where it is defined or declared;*

*2. Will leads to reference error until it is initialized; ( Will be in temporal dead zone)*

*3. Hoisting will not work*

*4. Cannot be declared more than once within the same block, for eg: switch;*

*5. Can be used as a private variable for a block, which can only be assessed with functions or var
   iables within that block.*

*6. If let is used to declare variable anywhere in the program, it will be in TDZ until it is initialized*

___


### Arrow Function

Eg 1.
```javascript
var d = (a) => a+1;
var e = x => x+1;
var f = () => { return; }
```
```javascript
Eg 2.
var g = () => ({})
```


Markup : * Used to eradicate function keyword

*.. In one line function, no need to return.*

*.. If multiple lines are there, then has to be kept in braces.*

*.. If there was single parameter, then no need to put in brace.*

*.. There is no arguments, this and super keyword within arrow function.*

*.. this keyword will always refer to global window inside arrow function.*

*.. While creating empty object if u write a program then always wrap in (). see eg2 *

___
