# Class 07 note

This document is about Domain Modeling, JavaScript Constructor Function, HTML Table. Domain Modeling is very important before starting solving a problem. Constructor function help us create an object without using object literal. HTML Table is a basic element in HTML document that commonly used to describe data, number, ...

## Reading

### Domain Modeling

1. *Explain why we need Domain Modeling*

Domain Modeling is the process of creating a conceptual model for a specific problem. A domain model that's articulated well can verify and vaidate the understanding of a specific problem. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

### HTML Table Basics

1. *Why should tables not be used for page layouts?*

    The main reasons are: 
    - Layout tables reduce accessibility for visually impaired users
    - Tables produce tag soup
    - Tables are not automatically responsive

2. *List and describe 3 different semantic HTML elements used in an HTML `<table>`*

    - `<td>` stands for table data, which is a cell in table
    - `<tr>` stands for table row, which defines a row in table
    - `<th>` stands for table header, which is a header in table

### Introducing Constructors

1. *What is a constructor and what are some advantages to using it?*

    Constructor is a function called using the `new` key word. When you call a constructor, it will create a new object and return the new object. Constructor help create many objects with the same attribute and method without using object literal for each object. 

2. *How does the term this differ when used in an object literal versus when used in a constructor?*

    `this` in object literal refers to the current object the code is being written inside. While when constructor called, it will bind `this` to the new object, so you can refer to `this` in your constructor code. 

### Object Prototypes Using A Constructor

1. *Explain prototypes and inheritance via an analogy from your previous work experience.*

    Prototype is way allow inheritance in JavaScript. Every function in JavaScript has `prototype` property. This property is an object. If we use constructor function to create objects, we can add properties or methods to constructor's prototype property. This allow inheritance in JavaScript. All instances created by constructor can access properties and methods of constructor's prototype. Each object has `prototype` attribute, refers to `prototype object` that the object inherited from. 

## Things I want to know more