# Class 04 notes

This document includes the next concept of HTML (creating hyperlink), CSS (CSS layout), and JS (function). Furthermore, this document includes some impotant notes about pair programming and its benefits.

## Learn HTML

1. *To create a basic link, we wrap text or other content inside what element?*

    To create a basic link, we wrap text or other content inside ans `<a>` element.

2. *The `href` attribute contains what information?*

    The `href` attribute contains the web address. 

3. *What are some ways we can ensure links on our pages are accessible to all readers?*

    - Include keywords in your link text to effectively describe what is being linked to.
    - Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a screen reader reads them out letter by letter.
    - Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users will also know there's a link, because links are generally styled in a different color and underlined (this convention generally shouldn't be broken, as users are used to it).
    - Keep your link text as short as possible — this is helpful because screen readers need to interpret the entire link text.
    - Minimize instances where multiple copies of the same text are linked to different places. This can cause problems for screen reader users, if there's a list of links out of context that are labeled "click here", "click here", "click here".

## CSS Layout

1. *What is meant by "normal flow"?*

    "normal flow" means the way that webpage elements lay themselves out if you haven't changed their layout.

2. *What are a few differences between `block level` and `inline` elements?*

    A `block level` element's content fills the available inline space of the parent element containing it, growing along the block dimension to accommodate its content.

    The size of `inline` element is just the size of its content.

3. *___ positioning is the default for every html element.*

    Static positioning is the default for every html element.

4. *Name a few advantages to using absolute positioning on an element.*

    We can create isolated UI features that don't interfere with the layout of other elements on the page

5. *What is a key difference between fixed positioning and absolute positioning?*

    Whereeas absolute positioning fixes an element in place relative to its nearest positioned usually fixes an element in place relative to the visible portion of the viewport.

## Learn JS

1. *Describe the differene between a function declaration and a function invocation.*

    A function declaration describes what that function do (what inside the function). Function invocation is used to execute the function code. The code inside a function is executed when the function is called.

2. *What is the difference between a parameter and an argument?*

    The values that are passed to function when it is called are arguments. Parameters are variables inside the function parentheses, in the function declaration.

## Miscellaneous

1. *Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.*

    - engaged collaboration
    - learning from fellow student

## Things I want to know more about


