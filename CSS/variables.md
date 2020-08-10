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
