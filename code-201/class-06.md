# Class 06 notes

This document give some important notes about objects in JavaScript and the DOM. Object is an important concept in programming and JavaScript usually works with objects. DOM also is an important concept, which explains how JS does with HMTL elements. 

## Reading

### JavaScript Object Basics

1. *How would you describe an object to a non-technical friend you grew up with?*

    An object is a collection of properties (describe the object) and methods (what the object can do).

2. *What are some advantages to creating object literals?*

    Creating object literals can bring some advantages when you want to transfer a series of structed, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.

3. *How do objects differ from arrays?*

    Object represent "things" with characteristics (aka properties), while arrays create and store lists of data in a single variable. Both object and array have bracket notation to access the items. The difference is while array using an index number to select an item, object using the name associated with each member's value. 

4. *Give an example for when you would need to use bracket notation to access an object's property instead of dot notation.*

    If an object property name is held in a variable, then you can't use dot notation to access the value, but you can acces the value using bracket notation.
    ```
    const Dog = {
        leg: 4,
        bark() {
            console.log("Gau Gau");
        }
    }
    
    function printProp(name){
        console.log(Dog[name]);
    }

    printProp("leg");
    ```
    
5. *Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?* 
```
    const dog = {
        name: 'Spot',
        age: 2,
        color: 'white with black spots',
        humanAge: function (){
            console.log(`${this.name} is ${this.age*7} in human years`);
        }
    }
```
The term `this` refer to `dog` object. The advantage of using `this` is it is enable to use the same method definition for every object you create. 

### Introduction to the DOM

1. *What is the DOM?*
    
    DOM is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page. 

2. *Briefly describe the relationship between the DOM and JavaScript.*

    Code is written in JavaScript, but uses the DOM to access the document and its element. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages. 

## Things I want to know more about
