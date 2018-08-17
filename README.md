# Snippet Study - Functions and Lexical Scope
  

## Description
This is about...


## Learning objectives (keywords)
<p>In this given snippet, the main points that came out were:</p>
  * Lexical Scope
  * Having more than 1 function point to the same function object

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
[repl.it]()  
[pythontutor]()  

S0. (State 0) you begin with the starting point: null   
S1. _to be continued_
   
Tracing table (deconstruction of input/output):
   
State nr. | State | Operation
------------|------------ | -------------
S0  | null |  
 . |  | Boolean (null)
S1 | false | 
. | | Void (undefined; "undefined")
S2 | undefined | 
. |  | Number (Number; Nan)
S3 | Nan | 
. |  | typeof (string; "Number")
S4 | "Number" | 
. | | "Number".toString
S5| "Number" | 
. | | typeof "number" (BECAUSE "number" is actually a string. "n-u-m-b-e-r"
S6 | "string" | 
## Vocabulary
   
## Review
* Struggles:   
  *   
* Learning objectives that need extra work?   
  *
* next steps:   
  * 
   
## Helpful links
