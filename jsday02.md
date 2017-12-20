# Javascript Exercise
**Javascript**
	- Difference between 'function declaration' and 'function expression':
	Function declarations load before any code is executed.
	Function expressions load only when the interpreter reaches that line of code.
	So if trying to call a function expression before it's loaded, will get an error! If call a function declaration instead, it'll always work, because no code can be called until all declarations are loaded. 
	- `parameters` in function using for:
		arguments listed in the function.
	-	Is there a max number of arguments javascript functions can accept:
	A function can have up to 255 arguments,but it depend on browser.