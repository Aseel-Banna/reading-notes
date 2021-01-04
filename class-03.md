# HTML
## Lists
- There are three types of lists:
  - **Ordered lists** are lists where each item in the list is numbered. 
  - **Unordered lists** are lists that begin with a bullet point (rather than characters that indicate order).
  - **Definition lists** are made up of a set of terms along with the definitions for each of those terms.
- The ordered list is created with the <**ol**> element and each item in the list is placed between an opening <**li**> tag and a closing </**li**> tag.
- The unordered list is created with the <**ul**> element and each item in the list is placed between an opening <**li**> tag and a closing </**li**> tag. 
- The definition list is created with the <**dl**> element and usually consists of a series of terms and their definitions.
  - <**dt**> This is used to contain the term being defined.
  - <**dd**> This is used to contain the definition.
- Nested Lists: You can put a second list inside an <**li**> element to create a sublist or nested list.

## Boxes
- You can control the dimensions of the box by set the width and height properties, but by default a box is sized just big enough to hold its contents. 
- You can use pixels, percentages, or ems, but the most popular one is using pixel
- Using percentages, the size of the box is relative to the size of the browser window.
- Using ems, the size of the box is based on the size of text within it.
- There is a limit for the width, using ***min-width*** and ***max-width***.
  - ***max-width*** property indicates the maximum width a box can stretch to when the browser window is wide.
  - ***min-width*** property is used to make sure that they do not appear too narrow.
- There is a limit for the height, using ***min-height*** and ***max-height***.
- The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. 
- ***hidden*** This property simply hides any extra content that does not fit in the box.
- ***scroll*** This property adds a scrollbar to the box so that users can scroll to see the missing content.
- Every box has three available properties that can be adjusted to control its appearance:
  - ***Border*** The border separates the edge of one box from another.
  - ***Margin*** sit outside the edge of the border.
  - ***Padding*** is the space between the border of a box and any content contained within it. 
- The **border-width** property is used to control the width of a border.
- You can control the style of a border using the **border-style** property. 
- You can specify the color of a border using either RGB values, hex codes or CSS color names.
- The **border** property allows you to specify the width, style and color of a border in one property.
- The **display** property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page.
- The **visibility** property allows you to hide boxes from users.
- The **border-image** property applies an image to the border of any box. 
- The **box-shadow** property allows you to add a drop shadow around a box.
- To create more complex shapes, you can specify different distances for the horizontal and the vertical parts of the rounded corners using border-radius.


# JavaScript
## Basic JavaScript Instructions
- An array is a special type of variable. It doesn’t just store one value; it stores a list of values.
- You create an array and give it a name just like you would any other variable (using the var keyword ollowed by the name of the array).
- Each item in an array is automatically given a number called an index.
- To retrieve any item on the list, the array name is specified along with the index number in square rackets.
- Each array has a property called length, which holds the number of items in the array.

## Decisions and Loops (Switch Statement)
- A switch statement starts with a variable called the switch value.  
- Each case indicates a possible value for this variable and the code that should run if the variable matches that value.  
- You have a default option that is run if none of the cases match.
- If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error. 
- The ***type coercion***: JavaScript can convert data types behind the scenes to complete an operation.
- JavaScript is said to use ***weak typing*** because the data type for a value can change.
- Falsy values are treated as if they are fa1se.
- Truthy values are treated as if they are true.  
- A unary operator returns a result with just one operand. 
- Logical operators are processed left to right. 
- Loops check a condition and the condition is true, then a block of code will run.
- For loop: is used when you need to run the code specific number of the code using counters to determine the number of running the code, conditions that have to be true to run the code and updating value.
- While loop: is used when you don’t know how many times you need to run the code.
- Do while loop: similar to while loop, but it will always run the statement inside the curly braces at least one.
- For loop is using counters as condition.
- There are keywords used by loops:
  - ***break***: This keyword causes the termination of the loop and tells the interpreter to go onto the next statement of code outside of the loop.
  - ***continue***: This keyword tells the interpreter to continue with the current iteration, and then check the condition again. 
  