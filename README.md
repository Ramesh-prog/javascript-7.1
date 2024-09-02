Intro to Javascript :- 

- Javascript is a High Level programming language for building web application in a efficient way. 
- Javascript works on both client side rendering as well as server side rendering.
- Node JS is the runtime environment of Javascript.
- Javascript is comes from echma script so we see the latest version of javascript in the form of echma script. 
- Now we used the javascript version 6 i.e Echmascript 6(ES6).
- In another way we called ES6 as the Vanilla Javascript. 
- Javascript is mainly used for building logics or functionality of a web page. 


Variable :- 

- Variable is a container to store some data. 
- There are 3 types of variable are there in Javascript. 

1. Let :- 

- Let is atype of variable which is used for changing the variable name latter. 
- Now these days, most of the developers used let for changing variable value.
- Let is a block scope so we have been using let for most of the cases. 

2. Var :- 

- Var is a type of variable which is also used for changing the variable in later stage.
- var is used in oldest browser so now a days we are don't use var most of the cases. 
- var is function or outside scope. 

3. Const :- 

- const is a type of variable where we can't change our data.
- const means constantto store some data like number, integer etc..

Rules for Creating Variable Name :- 

- variable names are case sensative i.e "a" & "A" is different.
- Only Letter, digits, Underscore & special character is allowed. (white space is not allowed).
- only letter, underscore & special character should be 1st character only. 
- reserved words cannot be a variable names

Datatypes in JS :- 

- Datatypes is an attributes associated with a piece of data that tells a computer system how to interprit its value. 
- In data types we used "typeof" operator to know that what type of data it is.
- mainly in javascript their are 2types of data types.

1. Primitive :- 
    - In javascript there are 7 types of primitive data types are present.
    
    1. Number :- Number are the type of data types those it contain some numerical value. 
    2. Boolean :- in Boolean data types we get boolean value like true & false
    3. Undefiend :- in Undefiend data types the data is not define so that it will show undefiend.
    4. Null :- In this data type we get null for the value means nothing.
    5. bigInt :- in bigint we will get big integer value
    6. String :- String is a type of data type that can hold some character like names or words
    7. Symbol :- in symbol we will get whole symbol as well as the value we get for the data type. 

2. Reference or Non-Primitive datatype :- 

- non-primitive datatypes are the type of data type that can hold multiple items in a a single time. 
- non primitive datatypes are - object, array & function
- objects is a non primitive datatype which can hold multiple of item in one single entity. 
- mainlly objects are working on ( key:value ) pair.
- the left hand side is our keys and right hand side are the values of that key. 

ex. of object:- 

person = {
    "name" : "web-Bocket",
    "age" : 2,
    "business" : "software",
    "carrier" : "good"
}

ex. of array:- 

let arr = [1,2,4,5,8,6,9,3,2]
note - array indexing start from "0".

ex. of function:- 

function great(){
    console.log("Hello World")
}
great()

Operator in Javascript :- 

- operator are the key features to do some task or operate some task. 
- ex. A + B 
- in that given example A & B are the operands , "+" sign is our operator. 
- There are 5 types of operator are their in javascript. 

1. Arithmetic Operator -> (+,-,*,/,%(Module), **(Exponents)).
2. Unary operator -> ++(increment) , --(Decrement)
3. Assignment Operator -> (=, +=, -=, *=,/=, %=, **=)
4. Logical Operator -> (Logical and operator - &&),(logical or operator ||)
5. Compairision Operator -> (==, !=, !==, ===)
