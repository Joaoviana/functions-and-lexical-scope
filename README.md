# Snippet Study - Functions and Lexical Scope
  

## Description
The given snippet is a good example of how referencing different variables to the same function object may or may not have an impact on your code. 

#### Lexical Scope
The word "lexical" refers to the fact that lexical scoping uses the location where a variable is declared within the source code to determine where that variable is available. Variables are used in the scope where they are defined. 

In the creation phase, the variables that are declared in the global scope are hoisted(this means that the variables that are declared outside of the function blocks are declared in the global scope). The function(s) template is created in the local scope so that when the function is executed, the machine will pass the arguments and the variables( declared in that function's local scope) and then return the value. 

## Learning objectives (keywords)
<p>In this given snippet, the main points that came out were:</p>

  * Lexical Scope 
  
  * Having more than 1 variable point to the same function object 

## Code snippet
```js
let arg = 0;
let meeyn = nyeem;
function nyeem(param) {
  var result = param;
  return result;
};
let ret_val = meeyn(arg);
console.log(ret_val);
```

## Trace Diagram

<a href="https://ibb.co/khdtfz"><img src="https://preview.ibb.co/mEDR0z/IMG_7007.jpg" alt="IMG_7007" border="0"></a>
   
## Helpful links
[A Drip Of JavaScript - Variable and Function Hoisting](http://adripofjavascript.com/blog/drips/variable-and-function-hoisting.html)
