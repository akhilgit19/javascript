# javascript
================
declaring a variable and intializing
=============================================
let a=1;// declaring a variable and intializing

reassiging the value of x
===========================
let x=1;
console.log(x);////1
x=20;// reassiging the value of x
console.log(x);////20

var number=1;

console.log(number);///1

number=123;
console.log(number)//123- reassiging the value of x

ConstVariable
================
const numbers =23;
console.log(numbers);///23
//
//numbers=24;
//console.log(numbers);/// Cannot reasssing to const variable

Typeof
========
let myName="Surya";

console.log(myName);

console.log(typeof(myName));


Solution:
===========
1
20
1
123
23
Surya
string

Mathemitacal Operators:
=========================
let number = 12345;

console.log(number);

//CamelCase
==============
let thisIsMyAnimeeName = "goku";

console.log(thisIsMyAnimeeName);

//snakecasse
==============
let this_is_my_goku_name = "vegu";

console.log(this_is_my_goku_name);

// a variable name can only contain alpha-numeric and underscore
==================================================================

//(a-z),(A-Z),(0-9),(_)

$
===
let $name = "goku";

_
===
let _name1 = "vegeta";
console.log($name);

Mathemitacal Operators
========================
let a = 1;

let b = 2;

console.log("sum is ", a + b);
console.log("sub is", a - b);
console.log("mul is ", a * b);
console.log("div is ", a / b);

console.log(10 % 2);
console.log(1 % 100000000);

Solution:
===========
~/Mathematical-Operators$ node problem.js

12345
goku
vegu
goku
sum is  3
sub is -1
mul is  2
div is  0.5
0
1

**
====
let a =2
let b=3
console.log("mul is",a**b);


let x=16;
console.log(x**0.5)

Solution:
===========
~/Mathematical-Operators$ node problem2.js
mul is 8
4

Contactenation
================
let a = "Hello";
let b ="World";

console.log(a,"",b);
console.log(a+" "+b);

Solution:
===========

~/Mathematical-Operators$ node problem3.js
Hello  World
Hello World

Boolean
==========
let married = false;
console.log(married);

let driving_license = true;

let name = "akhil";

let age = "26";
let gender = "male";
let has_driving_license = true;
let citizen_of_india = true;

console.log(name);

console.log(age);
console.log(gender);
console.log(has_driving_license);
console.log(citizen_of_india);

Solution:
===========
~/Mathematical-Operators$ node problem4.js
false
akhil
26
male
true
true


let a = 5;
let b = 5;
let c = 5;

let d = "Hello\n";
let e = "world";

//Create 3 varialbed do the square of the variable and sum of them

console.log(a ** 2 + b ** 2 + c ** 2); //75

console.log(d + e);

Solution:
===========

~/Mathematical-Operators$ node problem5.js
75
Hello
world


Relation Operators:
====================
let gokuHeight=6;

let vegitaHeight=5;
//Relational Operators
//a>b
//a<b
//a>=b
//a<=b


console.log(gokuHeight>vegitaHeight);
console.log(11>5);
console.log(11>=5);

Solution:
===========
~/Mathematical-Operators$ node problem6.js
true
true
true


Comaparison Operators:
========================

//There are 4 comparision operators

//double equal  to (==)

// not equal to (!=)
// triple equal to (===) it will check for value and // // datat type
// not triple euqal to(!==)

let a = "2";
let b = 2;
console.log(a == b); /// checks for the value
console.log(a != b); /// reverse of a==b
console.log(a === b); // checks for the value and data type
console.log(a !== b); // reverse of a===b

// relational operators
// //<,>,>=,<=
// Comparision operators
// //==,!=,===,!==

Solution:
===========
~/Mathematical-Operators$ node problem7.js
true
false
false
true
