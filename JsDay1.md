## Variables Declaration Revision

- Var
- Let
- Const
- When to use var,let,const

## Let & Const

```javascript
let x = "Htet Htet";

let x = 0;
//cannot be redeclared

const x = "Htet Htet";
const x = 0;
//cannot be redeclared

const x = 3;
x = 4; //can't updated

let x = 3;
x = 4; //can be updated
```

## var

```javascript
var name = "Htet";
var name = "Kyaw"; // No error
console.log(name); // Bob

var message = "Hello";
console.log(message); // Output: Hello

message = "World"; // can be reassigned
console.log(message); // Output: World
```

## Operators Revision

- Arithmetic Operators
- Assignment Operators
- Comparison Operators
- Logical Operators
- Ternary Operators

## Object Revision

- object property value can contain string,number,function
- can access object property value with dot notation and bracket notation
- nested object
- object destructuring

```javascript
const car = {
  brand: "Toyota",
  model: "2024",
};

const { brand, model } = car;
console.log(brand, model);
```

## Array Revision

- array data can access wiht index number
- some array methods (push,pop, shift, unshift,length,splice,)
- Array iteration methods (map,foreach, filter)

```javascript
const myarr = [1, 2, 3, 4, 5];

myarr.foreach((item) => {
  console.log(item);
});
// output is 1,2,3,4,5
```
- And array with for looping

## Conditional Statement
- if else if 
- switch
- condition checking with exam pass or fail 
