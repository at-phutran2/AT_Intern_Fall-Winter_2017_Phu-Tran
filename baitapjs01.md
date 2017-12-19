# AT_Intern_Fall-Winter_2017_Phu-Tran
**Javascript**
**differnce between null & undefined:**

- Undefined means a variable has been declared but has not yet been assigned a value. 
- On the other hand, null is an assignment value. It can be assigned to a variable as a representation of no value.
Also, undefined and null are two distinct types: undefined is a type itself (undefined) while null is an object.

**"use strict" is:**
- a literal expression.
advantage of using strict mode:
- track our code and catch common coding errors with these mistake:
  Duplicate keys in object.
  Variables without var
  Duplicate arguments
  Freezes the arguments of the functions
disadvantage:
  - It will not allow us to use the “with” statement. This statement will causes security and performance problems.

  - It will not allow us to use the “arguments.caller” property, due to security concernsWe do not have an alternate to this property, but we can hard code an additional parameter.

**differnce beetween == & ===**
  The == operator will compare for equality after doing any necessary type conversions. The === operator will not do the conversion, so if two values are not the same type === will simply return false.
  
**var let const**
    - let allows you to declare variables that are limited in scope to the block, statement, or expression on which it is used. 
    - var defines a variable globally, or locally to an entire function regardless of block scope.
    - const  The value of a constant cannot change through re-assignment, and it can't be redeclared.
### Playground
1. 
function sum(a,b){
  if (a === b) {
    return 3 * (a + b)
  } else 
    return a + b;
  }
console.log(sum(5,10));

2. 
function abs(num) {
  if (num < 19) {
    return 19 - num;
  } else if (num === 19) {
    return 0;
  } else 
    return 3 * (num - 19);
  }
console.log(abs(19));

3. 
function Replace(str) {
  let arr = [];
  for(let i = 0; i < 10; i++) {
    let num = str.replace('*', i);
    if(num % 3 === 0) {
      arr.push(num);
    }
  }
  return arr;
}
console.log(Replace('1234567890*'));

4. 
function Replace(str) {
  let arr = [];
  for(let i = 0; i < 10; i++) {
    let num = str.replace('*', i);
    if (num % 6 === 0) {
      arr.push(num);
    }
  }
  return arr;
}
console.log(Replace('1*9'));