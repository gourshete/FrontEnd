### Use CSS Variable

- An attribute value can be set to a variable so that it can be used at multiple places later without defining again(same like any other programming language)

- Here is how would you do it -

`
.penguin {
    --penguin-skin: black;
}
`

`
.penguin-top {
  background: var(--pengiun-skin);
}
`

----------------------------------------------

### Attach a Fallback value to a CSS Variable


- When using your variable as a CSS property value, you can attach a fallback value that your browser will revert to if the given variable is invalid.

- Here's how you do it:

`
background: var(--penguin-skin, black);
`

This will set background to black if your variable wasn't set.


----------------------------------------------

### Variable Inheritance

- When you create a variable, it is available for you to use inside the selector in which you create it. It also is available in any of that selector's descendants. This happens because CSS variables are inherited, just like ordinary properties.

- To make use of inheritance, CSS variables are often defined in the :root element.

- :root is a pseudo-class selector that matches the root element of the document, usually the html element. By creating your variables in :root, they will be available globally and can be accessed from any other selector in the style sheet.

`
:root {
    --penguin-belly: pink;
}
`

`
body {
    background: var(--penguin-belly, #c6faf1);
}
`

`
.penguin {
    --penguin-skin: black;
}
`
