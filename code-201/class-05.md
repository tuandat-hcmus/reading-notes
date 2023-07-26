# Class 05 notes

This document gives some important notes about how to use images in HTML, how to use color and how to style HTML text element by CSS. These concepts are first steps of working with media in HTML and making your web more beautiful.

## Learn HTML

1. *What is a real world use case for the `alt` attribute being used in a website?*

    Value of `alt` attribute is supposed to be a textual description of the image, for use in situation where the image cannot be seen/displayed or take long time to render. A real world use case is alternative text provide better image descriptions to search engine.

2. *How can you improve accessibility of images in an HTML document?*

    - for decoration, add a blank `alt=""`
    - If the image provides significant information, provide the same information if `alt` text. Don't write redundant `alt` text. If the image is describe adequately by the main text body, you can just use `alt=""`
    - If you put an image inside `<a>` tag, you still must provide accessible link text. Write it inside the same `<a>` element, or inside the image's `alt` attribute.
    - Avoid putting text into images.

3. *Provide an example of when the `figure` element would be useful in an HTML document.*

    For instance, we have a lot of images and each image need a caption. The `figure` element help us to provide a sementic container for images and link the image to the caption.

4. *Describe the difference between a `gif` image and a `svg` image, pretend you are explaining to an elder in your community?*

    - GIF is a good choice for simole images and animations. Each pixel of GIF is represented by a single 8-bit value serving as an index into a palette of 24-bit colors (8 bits each of red, green, and blue). GIF support simple animation, in which following an initial full-size frame, a series of images reflecting the parts of the image that that change with each frame are provided.
    - SVG is an vector graphics format that specifies the contents of an image as a set of drawing commands that create shapes, linws apply colors, filters, and so forth. SVG files are text files containing source code that, when interpreted, draws the desired image. 

5. *What image type would you use to display a screenshot on your website and why?*

    I would like to use PNG because PNG is a lossless format. Screenshot may contain some text, which can be fuzzy and unclear under lossy compression. 

## Learn CSS

1. *Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.*

    Forground colors of an element are the colors of its content and the background colors are the background colors of the HTML element.

2. *Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?*

    I would specifying colors in stylesheets to apply color to his blog's elements.

3. *What should you consider when choosing fonts for an HTML document?*

    The browser will ony apply a font if it is available on the machine the website is being accessed on; if not, it will just use a browser default font. There are only certain number of fonts that are generally available across all systems and can therefore be used without much worry (web safe fonts). Web safe fonts should be used.

4. *What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?*

    - `font-size` sets the size of the font in most of units, the most common units are: `px`, `em`, and `rem`
    - `font-weight` sets how bold the text is.
    - `font-style` used to turn italic text on or off. 

5. *Describe two ways you could add spacing around the characters displayed in an `h1` element.* 

    Two ways you could add spacing around the characters displayed
    - `line-height` property sets the height of each line of text. 
    - `letter-spacing` and `word-spacing` properties set the spacing between letters and words in your text.
