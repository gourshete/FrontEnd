## Use Hex Code to Mix Colors

- Hex codes use 6 hexadecimal digits to represent colors, two each for red (R), green (G), and blue (B) components.

- From these three pure colors (red, green, and blue), we can vary the amounts of each to create over 16 million other colors!

- For example, orange is pure red, mixed with some green, and no blue. In hex code, this translates to being #FFA500.

- The digit 0 is the lowest number in hex code, and represents a complete absence of color.

- The digit F is the highest number in hex code, and represents the maximum possible brightness.

**Examples** - 

Red	- #FF0000

Green	- #00FF00

Orange	- #FFA500

Dodger Blue -	#1E90FF


#### Shorthands for Hex codes -

- For example, red's hex code #FF0000 can be shortened to #F00. This shortened form gives one digit for red, one digit for green, and one digit for blue.

- This reduces the total number of possible colors to around 4,000. But browsers will interpret #FF0000 and #F00 as exactly the same color.

Red -	#F00

Green -	#0F0

--------------------------------------------------------------------------------------------

## Use RGB values to Color Elements

- Another way you can represent colors in CSS is by using RGB values.

The RGB value for black looks like this:

rgb(0, 0, 0)

The RGB value for white looks like this:

rgb(255, 255, 255)

- Instead of using six hexadecimal digits like you do with hex code, with RGB you specify the brightness of each color with a number between 0 and 255.

- If you do the math, the two digits for one color equal 16 times 16, which gives us 256 total values. So RGB, which starts counting from zero, has the exact same number of possible values as hex code.

Here's an example of how you'd change the body background to orange using its RGB code.

`
body {
  background-color: rgb(255, 165, 0);
}
`
