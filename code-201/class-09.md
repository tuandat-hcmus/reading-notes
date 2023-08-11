# Class 09 note

This document is about HTML form and JS events. Web forms are one of the main points of interaction between a user and a website or application. Events are things that happen in the system you are programming. These two concepts are important in web development. 

## HTML Forms

1. *Why are forms so important in web development?*

    Because web forms are one of the main points of interaction between a user and a website of application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way. 

2. *When designing a form, what are some key things to keep in mind when it comes to user experience?*

    It's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need. 

3. *List 5 form elements and explain their importance.*

    - `<form>` element formally defines a form and attributes that determine the form's behavior. Each time you want to create an HTML form, you must start it by using this element, nesting all the contents inside. 
    - `<fieldset>` element ís a convenient way to create a group of widgets that share the same purpose, for styling and semantic purposes. 
    - `<legend>` element is used to label a `<fieldset>`.
    - `<label>` element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms. 
    - `<input>` element define the field where users enter data. 

## Learn JS - Introduction To Events

1. *How would you describe events to a non-technical friend?*

    Events are things that happen in the system you are programming, which the system tells you about so your code can react to them. 

2. *When using the addEventListener() method, what 2 arguments will you need to provide?*

    - A string defines type of event. 
    - A function to call when the event happens.

3. *Describe the event object. Why is the target within the event object useful?*

    Sometimes, inside an event handler function, there is an parameter. This is called the **event object**, and it is automatically passed to event handlers to provide extra features and information. The `target` property of the event objects is always a reference to the element the event occured upon. Therefore, if there are many elements want to apply the same event handler function on themselves, the target within the event object is very useful. 

4. *What is the difference between event bubbling and event capturing?*

    The difference is the order. In event bubbling, event fires first on the innnermost element targeted, and then on successively less nested elements, while in event capturing, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached. 

## Things I want to know more about