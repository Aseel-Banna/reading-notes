# Forms
- Forms are used to enable users to search and allow them to perform other functions online.
- Forms are used to collect information from the user:
  - Adding Text:
     - Text input (single-line).
     - Password input.
     - Text area (multi-line).
  - Making Choices:
     - Radio buttons.
     - Checkboxes.
     - Drop-down boxes.
  - Submitting Forms:
     - Submit buttons.
     - Image buttons.
     - File upload.
- A form may have several form controls, each gathering different information. 
- Form controls live inside a <**form**> element.
- The <**input**> element is used to create several different form controls.
- You can decide the type of input elements using **type=**.
- The <**option**> element is used to specify the options that the user can select from.
- Each form has fields with different types such as email and password.
- The lists of making choices are also decided by **type=**.
- HTML5 introduces new form elements which make it easier for visitors to fill in forms.


# Lists
- The ***list-style-type*** property allows you to control the shape or style of a bullet point.
- For an unordered list you can use the following values:
  - none.
  - disc.
  - circle.
  - square.
- For an ordered (numbered) list you can use the following values:
  - decimal.
  - decimal-leading-zero.
  - lower-alpha.
  - upper-alpha.
  - lower-roman.
  - upper-roman.
- You can specify an image to act as a bullet point using the *list-style-image* property.
- *list-styleposition* property indicates whether the marker should appear on the inside or the outside of the box containing the main points. 
- Table Properities:
  - width.
  - padding.
  - text-transform.
  - letter-spacing and font-size.
  - border-top and border-bottom.
  - text-align.
  - background-color.
  - hover.
- The **border-spacing** property allows you to control the distance between adjacent cells. 
- You can use the same properities that used to set texts to set forms input too.
- You can set the style for the cursor.
- Table cells can have different borders and spacing in different browsers, but there are properties you can
use to control them and make them more consistent.


# Events
- Interactions Create Events.
- Event Trigger Code.
- Code Responds to Users.
- When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code:
  1. Select t he element node(s) you want the script to respond to.
  2. Indicate which event on the selected node(s) will trigger the response. 
  3. State the code you want to run when the event occurs. 
- Three Ways to Bind an Event to an Element.
  - HTML EVENT HANDLERS.
  - TRADITIONAL DOM EVENT HANDLERS.
  - DOM LEVEL 2 EVENT LISTENERS.
- element.onevent=functionName:
  - element: it is element.
  - oneevent: it is an event.
- Event listeners are a more recent approach to handling events. 
- Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround.  
- When an event occurs, the event object tells you information about the event, and the element it happened upon. 
- Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element. 
- The event object has methods that change: 
  - the default behavior of an element and how the element's ancestors respond to the event.
- When calling a function, the event object's target property is the best way to determine which element the event occurred on. 
- User interface CUI) events occur as a result of interaction with the browser window rather than the HTML page contained within it.
- The load event is commonly used to trigger scripts that access the contents of the page. 
- The mouse events are fired when the mouse is moved and also when its buttons are clicked. 
- The keyboard events are fired when a user interacts with the keyboard.
- Whenever elements are added to or removed from the DOM, its structure changes. 


  


 
