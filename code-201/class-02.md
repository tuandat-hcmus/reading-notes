# Class 02 notes

This topic is about some basic concepts of HTML, CSS and JS (continue from class 01). It is important to get the basic knowledge before going further in front-end development. 

## Learn HTML

1. *Why it is important to use semantic elements in our HTML?*

    Semantic elements gives us the correct meaning, function, or appearance of our content. Semantic value will be used in multiple ways, for example by search engines and screen readers. If we use elements that don't have semantic values, they won't get any extra benefits.

2. *How many levels of headings are there in HTML?*

    There are 6 levels of headings in HTML, from `<h1>` to `<h6>`.

3. *What are some uses for the `<sup>` and `<sub>` elements?*

    - `<sub>` for subscript
    - `<sup>` for superscript
    These two elements are used to mark up item like dates, chemical formulae, and mathematical equations so they have correct meaning.

4. *When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?*

    `<abbr>` is used to wrap around an abbreviation or acronym. When including either, provide a full expansion of the term in plain text on first use, along with the `<abbr>` to mark up the abbreviation. This provides a hint to user agents on how to announce/display the content while informing all users what the abbreviation means.

    If providing the expansion in addition to the abbreviation makes little sense, and the abbreviation or acronym is a fairly shortened term, provide the full expansion of the term as the value of `title` attribute.

## Learn CSS

1. *What are ways we can apply CSS to our HTML?*

    There are 3 ways of applying CSS to a HTML document: with an external stylesheet, with an internal stylesheet, and with inline styles.

2. *Why should we avoid using inline styles?*

    First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

3. *Review the block of code below and answer the following question*

    ```
    h2 {
        color: black;
        padding: 5px;
    }
    ```
    1. What is representing the selector?

        `h2` is representing the selector
    2. Which components are the CSS declarations?
        `color: black;` and `padding: 5px;`
    3. Which components are considered properties?
        `color` and `padding`

## Learn JS

1. *What data type is a sequence of text enclosed in single quote marks?*

    It is a `string` data type.

2. *List 4 types of JavaScript operators.*

    - Addition
    - Assignment
    - Strict equality
    - Subtraction

3. *Describe a real world Problem you could solve with a Function.*

    Give an integer `n`. You want to calculate the sum of all integer from `1` to `n`. This problem can be solved with a function. The main purpose is to reuse this function in oder to calculate the sum with different `n`.

### Conditionals

1. *An if statement checks a __ and if it evaluate to ___, then the code block will execute.*

    An if statement checks a **condition** and if it evaluate to **true**, then the code block will execute.

2. *What is the use of an `else if`?*
     An `else if` gives an extra choice (if we want more than two choices).

3. *List 3 different types of comparison operators*

    - `===`
    - `!==`
    - `<` and `>`

4. *What is the difference between the logical operator `&&` and `||`?*
    - `&&` - AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to `true` for the whole expression to return `true`.
    - `||` - OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to `true` for the whole expression to return `true`.

## Things I want to know more about
