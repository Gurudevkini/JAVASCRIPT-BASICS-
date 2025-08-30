# JAVASCRIPT-BASICS- 1
This repository contains my learning progress in JavaScript — from fundamentals (variables, functions, arrays, objects) to small projects. Each topic includes notes in the README and code examples in separate files.
JavaScript Notes
1. Printing Output
In C, we use `printf`. In JavaScript, we use `console.log()`.
console.log("Hello World");
2. Variables
A variable is like a container that stores data. Strings need double quotes, numbers don’t.
let name = "Gurudev";   // string
let age = 20;           // number
console.log(name);      // Gurudev
console.log(age);       // 20
Difference:
- console.log("age"); → prints the word age
- console.log(age); → prints the value stored in variable (20)
3. Booleans
Only two values:
true   // Yes / Correct
false  // No / Wrong
let isFollow = true;
console.log(isFollow);   // true
4. Operators
= → Assignment operator (stores value).
let age = 20;
== → Compares values.
=== → Compares values + types.
5. Variable Rules
Rules for naming variables:
• Variables are case sensitive (age and Age are different).
• Allowed characters: letters, digits, underscore (_), dollar ($).
• First character must be a letter, underscore (_), or dollar ($).
• Not allowed: spaces, symbols like @, #, %, or keywords (let, class, etc.).
6. Variable Naming Styles
Examples of naming styles:
• fullname → valid but not readable
• full_name → valid (snake_case)
• full-name → invalid ❌
• FullName → valid (PascalCase, used for classes)
• fullName → recommended (camelCase)
let fullName = "Gurudev";   // camelCase (preferred)
let full_name = "Gurudev";  // snake_case
let FullName = "Gurudev";   // PascalCase
7. var, let, const
Difference between var, let, and const:
var → old way (before ES6), function-scoped, can be redeclared and reassigned.
var age = 24;
var age = 56;   // works, but not recommended
let → introduced in ES6, block-scoped, cannot be redeclared in same scope, can be reassigned.
let age = 24;
age = 56;   // ✅ allowed
const → introduced in ES6, block-scoped, cannot be redeclared or reassigned. Must be initialized.
const PI = 3.14;   // written in ALL CAPS by convention


Summary Table:
Keyword	Redeclare	Reassign	Scope	Preferred Use
var	Yes	Yes	Function	Avoid
let	No	Yes	Block	Variables that change
const	No	No	Block	Constants, fixed values
Memory Tips
• var → Very old → avoid.
• let → Let it change.
• const → Constant, never changes.
