# Nodejs API

This is a simple nodejs REST API application.

## Task

You have two key task

1. Find and fix any bugs in the code
2. Add an API endpoint which takes JSON data and stores it in the file system

## Bonus Task

1. Refactor functions in `./src/controllers.js` to not require a callback argument but instead return data to the caller. e.g

### _Given_

```js
function sum(a, b, callback) {
  callback(a + b);
}

sum(1, 1, result => {
  console.log(result);
});
```

### _Expeccted_

```js
functions sum(a, b) {
  return a + b;
}

const result = sum(2, 3);
console.log(result);
```

2. Implement node cluster and ensure the app still runs as expected

## Running the Application

To run the REST API, in the root folder run `node .` or `node index.js`


# SOLUTIONS
What is Object oriented programming?
 Object oriented programming is basically designing of software using objects instead of using functions. The object will act as blueprints. It heavily used classes and inheritance to avoid repetition of code

What is functional programming?
  This a way of programming which heavily uses functions.Do not share data with other functions

What is testing? 
  This is the process of evaluating and validating if it is working as per the expectations

What frameworks are used for testing?
  - Linear Automation
  - Modular Driven
  - Behavior Driven
  - Data-Driven
  - Keyword-Driven
  - Hybrid Testing

What is version control?
  This is the process of tracking changes in my source code

What is the difference between undeclared & undefined variables?
  undeclared -> it does not exist anywhere in the source code
  undefined -> it is declared but has no value 

What are promises in JavaScript?
   It is a 'pregnant' object what is expected to return a value

Writing an Object
  const person = {
    fullname: "customer",
    age: Math.random(),
    fullName : function() {
      return this.fullname + " " + this.age;
    }
  };


What will be the output of the following code?
 	console.log(false == '0') // true

 	console.log(false === '0') // false

React/Js what is the virtual dom?
  - It is a not physically existing as such representation of document object model
  
React/Js what is the virtual dom?
  - using of props

React/Js what is the difference between useState & Useffect hook?
  useState allows our functional components which used to be stateless become stateful. And useEffect allows our functional components leverage the component lifecycle hook

What is the difference between  Class and Functional components?
  functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React

What is the difference between state and props?
   State is the local data of a component(component based data) but props are data passed from one component to the other

What are controlled/uncontrolled components?
  Controlled - takes props and notifies them through callbacks on changes
  Uncontrolled - stores its data internally

What is a higher order component?
  Technique of reusing a component

What is the purpose of `render()` function?
  display the specified HTML code inside the specified HTML element

What is the difference between React Native and React?
  React native is for building mobile apps while react is for building web apps

What is GCP?
  Platform that offers information technology services

What is App Engine?
 A cloud computing platform for developing and hosting web services  in google managed data centers

What is the difference between Software as a Service and Platform (SaaS) as a Service (Paas)?
   PaaS, or platform as a service, is on-demand access to a complete, ready-to-use, cloud-hosted platform for developing, running, maintaining and managing applications.
   SaaS, or software as a service, is on-demand access to ready-to-use, cloud-hosted application software

What is Infrastructure as Code and why is it important in the modern server environment
   Infrastructure as a code is important for efficiency of the server

What is Infrastructure as a Service (IaaS)?
  Offers storage and networking services 

What is a class C network address
  It is a memory consisting of a 24-bit network address and an 8-bit local host address 

What is a “port number” and why is it used
 A port number is a way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server

What is javascript? 
 JavaScript is a scripting language that enables you to create dynamically updating content

What are the data types supported by JavaScript?
    Boolean type.
    Null type.
    Undefined type.
    Number type.
    BigInt type.
    String type.
    Symbol type

How can you create an object in JavaScript?
  {
    prop1: '',
    prop2: ''
  }

What is NaN in JavaScript?
  NaN is a number that is not a legal number

What is the difference between Call & Apply?
  call method takes arguments separately. 
  apply method takes arguments as an array

How does Node.js work?

Explain callback in Node.js

What are the advantages of using promises instead of callbacks?




How would you connect a Postgresql database to Node.js?




What is callback hell?

What is REPL in Node.js?

What is node cluster and how do you use it?







