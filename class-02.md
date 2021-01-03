# HTML
## Text
- There are six levels of heading:
  - h1 for the main title, which is the biggest font size.
  - h2 for subtitles, which is smaaller than h1.
  - h3, h4, h5, h6 are smaller than h1. So, h6 is the smallest one.
- <**p**> the paragraph tag is used to write a pragraph. 
- There are tags used to set the property of the text such as bold and italic.
  - For bold text, you can use <**b**>.
  - For italic text, you can use <**i**>.
- Also, there are some tags that are used to superscript or subscript text. 
  - <**sup**> is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts.
  - <**sub**> is used  to contain characters that should be subscript.
- Using <**br**> tag, you can add a line break inside the middle of a paragraph.
- Using <**hr**> tag, you can create a break between themes.
- There are two views of the HTML page that you are creating:
  - Visual Editor: often resemble word processors. 
  - Code View: show you the code created by the visual editor so you can manually edit it, or just enter new code.
- Semantic Markup: they are some text elements that are not intended to affect the structure of your web ages, but they do add extra information to the pages.
- The <**strong**> tag indicates that its content has strong importance.
- The <**em**> tag indicates emphasis that subtly changes the meaning of a sentence.
- The <**blockquote**> tag is used for longer quotes that take up an entire paragraph. 
- The <**q**> tag is used for shorter quotes that sit within a paragraph. 
- The <**abbr**> tag is used to use an abbreviation or an acronym.
- The <**cite**> tag can be used to indicate where the citation is from.
- The <**dfn**> tag is used to indicate the defining instance of a new term.
- The <**address**> tag has is used to contain contact details for the author of the page.
- The <**ins**> tag can be used to show content that has been inserted into a document.
- The <**del**> tag can show text that has been deleted from it.
- The <**s**> tag indicates something that is no longer accurate or relevant (but that should not be deleted).

## Introduction to CSS
- CSS works by associating rules with HTML elements.
- A CSS rule contains two parts: a *selector* and a *declaration*.
  - Selectors indicate which element the rule applies to. 
  - Declarations indicate how the elements referred to in the selector should be styled. 
- CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. 
  - Properties indicate the aspects of the element you want to change. 
  - Values specify the settings you want to use for the chosen properties.
- The <**link**> tag can be used in an HTML document inside the <**head**> to tell the browser where to find the CSS file used to style the page.
- ***href*** specifies the path to the CSS file.
- ***type*** specifies the type of document being linked to.
- ***rel*** specifies the relationship between the HTML page and the file it is linked to.
- You can use inline css using <**style**> inside the <**head**> tag.
- Types of selector:
  - Universal Selector: Applies to all elements in the document.
  - Type Selector: Matches element names.
  - Class Selector: Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol.
  - ID Selector: Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol.
  - Child Selector: Matches an element that is a direct child of another.
  - Descendant Selector: Matches an element that is a descendent of another specified element (not just a direct child of that element).
  - Adjacent Sibling Selector: Matches an element that is the next sibling of another.
  - General Sibling Selector: Matches an element that is a sibling of another, although it does not have to be the directly preceding element.

- Using external style sheet can allow all web pages sharing the same style sheet.
- Once the user has downloaded the CSS stylesheet, the rest of the site will load faster.
- There are different versions of CSS such as CSS1, which was released in 1996 and CSS2, which is followed two years later.

# JavaScript
## Basic JavaScript Instructions
- JavaScript is case sensitive.
- A statement is an individual instruction that the computer should follow.
- Code Blocks are some statement that are surrounded by curly braces.
- Comments are used to explain what your code does.
  - Single Line Comment: // 
  - Multi Line Comment: /*
- Variables: storing the bits of information it needs to do its job.
- To write a variable you should use ***var*** as a keyword and then the name of the  followed by the assignment oparater and the the value.
- Data Types:
  - Numeric: using variables to store numbers.
  - String: using variables to store texts.
  - Boolean: using variables to get true or false statment.
- Variables can be used to store numaric values. Also, variables can be used to store string values by using single quotes.
- Rules for naming variables:
  - The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
  - The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.
  - You cannot use keywords or reserved words.
  - All variables are case sensitive.
  - Use a name that describes the kind of information that the variable stores.
- An array is a special type of variable. It doesn't just store one value; it stores a list of values. 
- You create an array and give it a name just like you would any other variable (using the var keyword ollowed by the name of the array). 
- Each item in an array is automatically given a number called an index.
- To retrieve any item on the list, the array name is specified along with the index number in square rackets. 
- Each array has a property called length, which holds the number of items in the array. 
- An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 
- Expressions rely on things called operators; they allow programmers to create a single value from one or more values. 


## Decisions and Loops
- There are two components to a decision:
  1. An expression is evaluated, which returns a value.
  2. A condition statement says what to do in a given situation.
- You can evaluate a situation by comparing one value or more.
- Comparison Operators
  - == : compares values of any data type. It retuns true if the values are equal to each other and false if they are not.
  - != : compares values of any data type. It retuns true if the values are not equal to each other and false if they are equal.
  - === : compares values of the same data type. It retuns true if the values and the data type are equal to each other and false if they are not.
  - !=== :compares values of the same data type. It retuns true if the values and the data type are not equal to each other and false if they are equal in value and same data type.
  - > : compares values and returns true if the first value is greater than the other one.
  - < : compares values and returns true if the first value is smaller than the other one.
  - >= : compares values and returns true if the first value is greater or equal the other one.
  - <= : compares values and returns true if the first value is smaller or equal the other one.

- Logical Operators
  - && : it can test more than one condition and return true if both of them are true.
  - || : it can test more than one condition and return true if any one of them is true.
  - ! : it takes one single condition and reveres the state of a statment.

- If Statement: it is used to check a condition.

