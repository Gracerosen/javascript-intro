# Introduction-to-Javascript-for-testing-in-code


This is intended only as an introduction and summary - these principals can be applied in theory in various ways and tested to memorise statements, see what data they can return, implement multiple data types into one application, evaluate literals, perform various calculations, call functions or methods in different ways, run tests, represent data in different ways, apply best practice, and create simple applications using the basics - obviously this can be extended and built upon further.

In some of my other repos i have mini apps using these principals/concepts for example calculators, sign in pages, games or timetables.






<strong>Methods</strong>
	(return info on an object/ called by appending an instance with a period ., the method name, and parentheses.) see example to test/expand on:

// Returns a number between 0 and 1
Math.random();



<strong>Libraries<.strong> - contain methods that can be called by appending the library name with a period ., the method name, and a set of parentheses.

Math.random();
// ☝️ Math is the library




<strong>console.log()</strong> method used to log or print messages to the console. It can also be used to print objects and other info.

console.log('Hi there!');
// Prints: Hi there!





<strong>Numbers</strong> (primitive data type. incorporates the set of all integers and floating point numbers.)

let amount = 6;
let price = 4.99;



<strong>String .length</strong> - The .length property of a string returns the number of characters that make up the string.

let message = 'good nite';
console.log(message.length);
// Prints: 9
 
console.log('howdy'.length);
// Prints: 5






<strong>Data Instances</strong> (the program keeps track of new data in an instance of that data type. An instance is an individual case of a data type.)





<strong>Booleans</strong> (a primitive data type. true or false.)

let lateToWork = true;





<strong>Math.random()</strong>
The Math.random() function returns a floating-point, random number in the range from 0 (inclusive) up to but not including 1.

console.log(Math.random());
// Prints: 0 - 0.9








<strong>Math.floor()</strong> function returns the largest integer less than or equal to the given number.

console.log(Math.floor(5.95)); 
// Prints: 5











<strong>Single Line Comments</strong> (created with two consecutive forward slashes //.)

// This line will denote a comment










<strong>Null</strong> (primitive data type) which represents the intentional absence of value. In code, it is represented as null.

let x = null;











<strong>Strings</strong> (pprimitive data type. any grouping of characters (letters, spaces, numbers, or symbols) surrounded by single quotes ' or double quotes ".

let single = 'Wheres my bandit hat?';
let double = "Wheres my bandit hat?";










<strong>Arithmetic Operators</strong> - JavaScript supports arithmetic operators for:

+ addition
- subtraction
* multiplication
/ division
% modulo



// Addition
5 + 5
// Subtraction
10 - 5
// Multiplication
5 * 10
// Division
10 / 5
// Modulo
10 % 5








<strong>Multi-line Comments</strong> (created by surrounding the lines with /* at the beginning and */ at the end. Comments are good ways for a variety of reasons like explaining a code block or indicating some hints, etc.)

/*  
The below configuration must be 
changed before deployment. 
*/
 
let baseUrl = 'localhost/taxwebapp/country';









<strong>Remainder / Modulo Operator</strong>
The remainder operator, sometimes called modulo, returns the number that remains after the right-hand number divides into the left-hand number as many times as it evenly can.

// calculates # of weeks in a year, rounds down to nearest integer
const weeksInYear = Math.floor(365/7);
 
// calcuates the number of days left over after 365 is divded by 7
const daysLeftOver = 365 % 7 ;
 
console.log("A year has " + weeksInYear + " weeks and " + daysLeftOver + " days");











<strong>Assignment Operator</strong> (assigns a value to its left operand based on the value of its right operand.) Here are some of them:

+= addition assignment
-= subtraction assignment
*= multiplication assignment
/= division assignment


let number = 100;
// Both statements will add 10
number = number + 10;
number += 10;
console.log(number); 
// Prints: 120







<strong>String Interpolation</strong> (the process of evaluating string literals containing one or more placeholders (expressions, variables, etc).It can be performed using template literals: text ${expression} text.

let age = 7;
// String concatenation
'Tommy is ' + age + ' years old.';
// String interpolation
`Tommy is ${age} years old.`;







<strong>Variables</strong> -  whenever there’s a need to store data that can be used in the program - ensures code re-usability 

const currency = '$';
let userIncome = 85000; 
console.log(currency + userIncome + ' is more than the average income.');
// Prints: $85000 is more than the average income.

Undefined ( a primitive JavaScript value that represents lack of defined value. Variables that are declared but not initialized to a value will have the value undefined.)

var a;
console.log(a); 
// Prints: undefined









<strong>Javascript: Variables</strong> - a data container stored in computer memory & referenced by a descriptive name that a programmer can call to assign a specific value and retrieve it.

// examples of variables
let name = "Tammy";
const found = false;
var age = 3;
console.log(name, found, age);
// Tammy, false, 3









<strong>Declaring Variables</strong> (const or var or let all declare variable and can all mean the same thing - variables declared by different keywords (const, let, var) ) 
any of these three keywords can be used along with a variable name:

var is used in pre-ES6 versions of JavaScript.
let is the preferred way to declare a variable when it can be reassigned.
const is the preferred way to declare a variable with a constant value.


var age;
let weight;
const numberOfFingers = 20;










<strong>Template Literals</strong> - strings that allow embedded expressions, ${expression}. While regular strings use single ' or double " quotes, template literals use backticks instead.

let name = "Codecademy";
console.log(`Hello, ${name}`); 
// Prints: Hello, Codecademy
console.log(`Billy is ${6+8} years old.`); 
// Prints: Billy is 14 years old.








let Keyword - let creates a local variable in JavaScript & can be re-assigned. Initialization during the declaration of a let variable is optional. A let variable will contain undefined if nothing is assigned to it.

let count; 
console.log(count); // Prints: undefined
count = 10;
console.log(count); // Prints: 10









<strong>const Keyword</strong>
A constant variable can be declared using the keyword const. It must have an assignment. Any attempt of re-assigning a const variable will result in JavaScript runtime error.

const numberOfColumns = 4;
numberOfColumns = 8;
// TypeError: Assignment to constant variable.







<strong>String Concatenation</strong> - multiple strings can be concatenated together using the + operator. In the example, multiple strings and variables containing string values have been concatenated. After execution of the code block, the displayText variable will contain the concatenated string.

let service = 'credit card';
let month = 'May 30th'; 
let displayText = 'Your ' + service  + ' bill is due on ' +  month + '.';
console.log(displayText);
// Prints: Your credit card bill is due on May 30th.


This is intended only as an introduction and summary - these principals can be applied in theory in various ways and tested to memorise statements, see what data they can return, implement multiple data types into one application, evaluate literals, perform various calculations, call functions or methods in different ways, run tests, represent data in different ways, apply best practice, and create simple applications using the basics - obviously this can be extended and built upon further.

In some of my other repos i have mini apps using these principals/concepts for example calculators, sign in pages, games or timetables.
