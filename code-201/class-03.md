# Class 03 notes

## Learn HTML

1. *when should you use an `unordered list` in your HTML document?*

    `unordered list` should be used to group a collecion of items that do not have a numerical ordering, and their order in the list is meaningless. 

2. *How do you change the `bullet style` of unordered list items?*

    There are two ways that you can change the `bullet style` of unordered list items:
    - Change the `type` atrribute of `<ul>` element.
    - using `list-style-type` property in CSS.

3. *When should you use an `ordered list` vs an `unorder list` in your HTML document?*

    Both `ordered list` and `unordered list` are used to group a collection of items. `ordered list` should be used if the order is meaningful. Otherwise, `unordered list` should be used.

4. *Describe two ways you can change the numbers on `list items` provided by an `ordered list`?*

    - specify the `type` attribute of `<ol>` element
    - specify the `list-style-type` property.

## Learn CSS

1. *Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: "The Box Model"?*

    - Margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements. `margin` property is used to size the margin.

    - Padding sits around the content as white space. `padding` property is used to size the padding.

2. *List and describe the four parts of an HTML elements box as referred to by the `box model`.*

    - content box: The area where your content is displayed; size it using properties like `inline-size` and `block-size` or `width` and `height`.

    - Padding box: The padding sits around the content as white space; size it using `padding` and related properties.

    - Border box: The border box wraps the content as white space; size it using `border` and related properties.

    - Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using `margin` and related properties.

## Learn JS

1. *What `data types` can you stored inside of an `Array`?*
    
    In array we can store various data types - strings, numbers, objects, and even other arrays.

2. *Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?*

    ```
    const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
    ```
 

    `people` array is a valid JavaScript array. You can access the values stored using bracket notation and supplying the item's index. In this case, each item is an array. Therefore you can access values inside an item by chaining two sets of square brackets together. 

3. *List **five** shorthand operators for assignment in javascript and describe what they do.*

    | Shorthand operator  | Meaning  |
    | ------------------- | ------  |
    | `x += f()`          | `x = x + f()`|
    | `x -= f()`          | `x = x - f()`|
    | `x *= f()`          | `x = x * f()`|
    | `x <<= f()`         | `x = x << f()`|
    | `x **= f()`         | `x = x ** f()`|

4. *Read the code below and evaluate the last `expession` and explain what the result would be and why.*

    ```
    let a = 10;
    let b = 'dog';
    let c = false;

    //evaluate this
    (a + c) + b;
    ```
    First, `a + c` will be evaluated. `c` is equal to `false` so `c` turns into `0`. Therefore `a + c` equal `10 + 0 = 10`. `b` is string so `10` will be converted into string. Then, the answer is `10dog`.

5. *Describe a real world example of when a conditioncal statement should be used in a JS program.*

    An example is when solving quadratic equation. 

6. *Give an example of when a `Loop` is useful in JavaScript.*

    Give a large array, we want to do the same thing with all the items of the given array. Because we can access items by using index, the loops will become useful in this case.

## Things I want to know more about
