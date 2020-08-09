E.g.


<style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }

  .pink-text {
    color: pink;
  }
</style>
<h1 class="pink-text">Hello World!</h1>
Note - read above code in edit mode to see h1 tags

<br>

- Precedence of elements

Sometimes your HTML elements will receive multiple styles that conflict with one another.

For example, your h1 element can't be both green and pink at the same time.

Let's see what happens when we create a class that makes text pink, then apply it to an element. Will our class override the body element's color: green; CSS property?

Create a CSS class called pink-text that gives an element the color pink.

Give your h1 element the class of pink-text.

Result - 

Reference-image: 
![prioritise-element image][negative-margin]

[prioritise-element]: images/prioritize-one-style-over-another.png "Margin"


h1 element style is prioritised over body element style. Will be safe to conclude - **styles will be picked from nearest element's style**



----------------------------------------------------------------------------------

- Precedence of classes

We just proved that our classes will override the body element's CSS. So the next logical question is, what can we do to override our pink-text class?

Create an additional CSS class called blue-text that gives an element the color blue. Make sure it's below your pink-text class declaration.

Apply the blue-text class to your h1 element in addition to your pink-text class, and let's see which one wins.

Applying multiple class attributes to a HTML element is done with a space between them like this:

class="class1 class2"

Note: It doesn't matter which order the classes are listed in the HTML element.

However, the order of the class declarations in the <style> section is what is important. The second declaration will always take precedence over the first. Because .blue-text is declared second, it overrides the attributes of .pink-text
  
  
----------------------------------------------------------------------------------

- Precedence between class and id

In the conflict of order between `class` & `id`, `id` will always take higher precedence.

----------------------------------------------------------------------------------

- Precedence of inline CSS

Inline CSS will take higher precedence over element's style defined inside style block above or in a css file

----------------------------------------------------------------------------------

- !important

This will be used with highest precedence.
