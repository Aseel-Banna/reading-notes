# What is an object?
- Objects group a set of variables and functions together.
- Variables in object called properities.
- Functions in object called methods.
- Objects store in variable.
- Name of an object is called key.
- Objects consist of a set of name or value pairs.
- Literal notation is the easiest and most popular way to create objects.
- The ***this*** keyword is used to indicate that their is something used from the object.
- You can access the properities of an object using dot notation.


# Document Object Model
- The web page creates a model when a browser loads a web page, whic is called ***DOM tree***.
- The DOM Node:
  - Every element, attribute, and piece of text in the HTML is represented by its own **DOM node**.
- The Elements Nodes:
  - HTML elements describe the structure of an HTML page.
- The Attribute Nodes:
  - The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree. 
- The Text Nodes:
  - Text nodes cannot have children. Once you have accessed an element node, you can then reach the text within that element. 

- Accessing and updating the DOM tree involves two steps:
  1. Locate the node that represents the element you want to work with. 
  2. Use its text content, child elements, and attributes. 

- Methods that finds in the elements in the DOM tree are called DOM queries.
- DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 
  - If a method can return more than one node, it will always return a Nodelist, which is a collection of nodes.
- Finding the quickest way to access an element within the web page will make the page seem faster and/or more responsive. This usually means evaluating the minimum number of nodes on the way to the element you want to work with.
- You can get elements by:
  - By ID.
  - By Class Name.
  - By Tag Name.
  - By Selector.
- You can use this way:
  - *object.method().*
- A Nodelist is a collection of element nodes.
- Collection: Nodelists look like arrays and are numbered like arrays.
- The length property indicates how many items are in the Nodelist.
- The item() method returns a specific node from the Nodelist when you tell it the index number of the item that you want (in the parentheses). 
- In a live Nodelist, when your script updates the page, the Nodelist is updated at the same time.
- In a static Nodelist when your script updates the page, the NodeList is not updated to reflect the changes made by the script.
- You can use loops within Nodelist.
- When you have an element node, you can select another element in relation to it using these five properties:
  - parentNode 
  - previousSibling 
  - nextSibling 
  - firstChild
  - lastChild
- When you select a text node, you can retrieve or amend the content of it using the **nodeVa1ue** property.
- The **textContent** property allows you to collect or update just the text that is in the containing element (and its children).  
- The innerHTML property: you can access and amend the contents of an element, including any child elements. 
  - Approach.
  - Adding Content.
  - Removing Content.
- ADVANTAGES
  • You can use it to add a lot of new markup using less code than DOM manipulation methods.
  • It can be faster than DOM manipulation when adding a lot of new elements to a web page.
  • It is a simple way to remove all of the content from one element (by assigning it a blank string).
- DISADVANTAGES
  • It should not be used to add content that has come from a user (such as a username or blog comment), as it can pose a significant security risk which is discussed over the next four pages.
  • It can be difficult to isolate single elements that you want to update within a larger DOM fragment.
  • Event handlers may no longer work as intended. 
- DOM manipulation offers another technique to add new content to a page:
  - createElement ().
  - createTextNode().
  - appendChild().
- The document object's write () method is a simple way to add content that was not in the original source code to the page, but its use is rarely advised. 
- ADVANTAGES
  • It is a quick and easy way to show beginners how content can be added to a page.
- DISADVANTAGES
  • It only works when the page initially loads.
  • If you use it after the page has loaded it can:
   1. Overwrite the whole page
   2. Not add the content to the page
   3. Create a new page
  • It can cause problems with XHTML pages that are strictly validated.
  • This method is very rarely used by programmers these days and is generally frowned upon.

- VALIDATE INPUT GOING TO THE SERVER:
  - Only let visitors input the kind of characters they need to when supplying information.
  - Double-check validation on the server before displaying user content/storing it in a database.
  - The database may safely contain markup and script from trusted sources.
  - As your data leaves the database, all potentially dangerous characters should be escaped.
  - Make sure that you are only inserting content generated by users into certain parts of the template files.
  - Do not create DOM fragments containing HTML from untrusted sources.

- XSS: VALIDATION & TEMPLATES:
  - Folter or validate input.
  - Limit where user content goes.
  - Escaping user content.
  - Adding user content.

- The **className** property allows you to change the value of the cl ass attribute. 
- To remove an attribute from an element, first select the element, then call **removeAttribute()**.  
- ***Firefox*** has similar built-in tools, but you can also download a DOM inspector tool that shows the text nodes. 
- 

 
  





