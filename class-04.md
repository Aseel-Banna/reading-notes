# HTML
### Links
- You can create links by using <**a**> and specify the page that you want to link by using the ***href*** attribute.
- ***URL*** stands for Uniform Resource Locator.
- The **Absolute URL**:  the full web address for the site.
- The Relative URL: it is a shorthand and you do not need to specify the domain name in the URL.
- **Structure** it is the diagram on the right shows the directory structure for a fictional entertainment listings website called ***ExampleArts***.
- **Relationships** The relationship between files and folders on a website is described using the same terminology as a family tree. 
- **Homepages** it is the main homepage of a site written in HTML which is **index.html**.
- Relative URLs can be used when linking to pages within your own website. 
  - Same Folder: to link to a file in the same folder, just use the file name. 
  - Child Folder: use the name of the child folder, followed by a forward slash, then the file name.
  - Grandchild Folder: use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name.
  - Parent Folder: use **../** to indicate the folder above the current one, then follow it with the file name.
  - GrandParent Folder: repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name.
- You can create a link that starts up with the user's email program and addresses an email to a specified email address using <**a**>.
- Using the **target** attribute in the opening <**a**>, then the link will open in a new window.
- To link to an element that uses an ***id*** attribute you use the <**a**> but changing the **href** and make it starts with the **#** symbol, followed by the value of the **id** attribute.
- You can either link to the top section of your webpage or to the bottom.


### Layout
- The HTML box will be either block-level box or inline box.
- The block-level box starts on a new line.
- The inline flows in between surrounding text.
- Containing Elements: when one block-level element sits inside another block-level element.
- Normal flow: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. 
- Relative Positioning: This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
- Absolute positioning: This positions the element in relation to its containing element.
- The **box offset** property is used to tell the browser how far from the top or bottom and left or right it should be placed.
- To use normal flow, you can set this property to **position: static**;
- To use relative position, you can set this property to **position: relative**;
- To use absolute position, you can set this property to **position: absolute**;
- To use fixed position, you can set this property to **position: fixed**;
- Using float property you can set where the index will appear.
- width: This sets the width of the columns.
- float: This positions the columns next to each other.
- margin: This creates a gap betweeen the columns.
- There are some other factors that you have to consider when you are creating a web page such as:
  - Screen Sizes.
  - Screen Resolution.
  - Page Sizes.
- Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. 
- Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window.
- Many designers use a grid structure to help them position items on a page, and the same is true for web designers.
- CSS frameworks aim to make your life easier by providing the code for common tasks.
- You can link your HTML page to a css files using (@import or <**link**>).



# JavaScript
### Functions, Methods, and Objects
- Functions let you group a series of statements together to perform a specific task. 
- You can perform the functions by **calling** them after **declaring** them.
- The function has parameters, that are placed between parentheses.
- The function can have a return value, but void function does not have.
- Declaring a function:
  - **function**, which is a keyword.
  - The name of the function followed by parentheses.
  - The curly brakets which have a block of code.
- You can call the function by its name and you can fill your own parameters.
- You can create a function either by:
  - Declaring Function: A function declaration creates a function that you can call later in your code.
  - Function Expression: If you put a function where the interpreter would expect to see an expression, then it is treated as an expression.
- Variable Scope: 
  - Local Variables: When a variable is created inside a function using the var keyword, it can only be used in that function.  
  - Global Variables: When a variable is created inside a function using the var keyword, it can only be used in that function.
- Global variables use more memory. 


### Article: 6 Reasons for Pair Programming 
[6 Reasons for Pair Programming]('https://www.codefellows.org/blog/6-reasons-for-pair-programming') 
- Improving the quality, you can use iterative loops, code reviews, fast feedback and error checking and linting.
- Pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together. 
- Pair Programming involves two roles: the Driver and the Navigator.
  - The Driver is the programmer who is typing and the only one whose hands are on the keyboard.
  - The Navigator uses their words to guide the Driver but does not provide any direct input to the computer.
- Pair Programming use skills of developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves. 
- Greater efficiency: It is a common misconception that pair programming takes a lot longer and is less efficient.
- Engaged collaboration: When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.
- Learning from fellow students: Working with a teammate can expose developers to techniques they otherwise would not have thought of.
- Social skills: When working with someone who has a different coding style, communication is key.
- Job interview readiness: The current employee and an applicant will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base.
- Work environment readiness: Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.

