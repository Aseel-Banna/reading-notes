# HTML 

### Structure
- The Structure of a web page is the elements inside this web page such as titles, subtitles, paragraphs, ...etc.
- Elements are characters that live inside angled brackets in HTML code. They are usually between two tags, opening tag and closing tag which has an extra forward slash inside it.
- Tags begin with "<>" and end with "</>".
- Some exampels for tags and their use:
  - The <**html**> tag indicates that anything between it is HTML code.
  - The <**body**> tag indicates that anything between it should be shown inside the main browser window.
  - The <**h1**> tag is the main heading. There are 6 types of headings and they are different. 
     - <**h1**> is the biggest font size.
     - <**h6**> is the smallest font size.
  - The <**p**> tag is a paragraph of text.
  - The <**title**> tag is shown in the top of the browser (Tap name).
  - The <**div**>  element allows you to group a set of elements together in one block-level box.
  - The <**span**> element acts like an inline equivalent of the <**div**> element. It is used to either:
     1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text.
     2. Contain a number of inline elements.
- Opening tags may contain **attributes** which provide additional information about the contents of an element.
- Attributes are made up of two parts: a name and a value, separated by an equals sign.
- All attributes names are written in lowercase and it indicates what kind of extra information for the contents.
- The value is the information or setting for the attribute. It should be placed in double quotes.
- HTML is **"HyperText Markup Language"**. 
   - The HyperText part allows you to create links that allow visitors to move from one page to another uickly and easily.
   -  A markup language allows you to annotate texts that provide additional meaning to the contents of a document.
- HTML pages are text documents.


### Extra Markup
- There are different versions of HTML such as HTML 4 which released 1997, XHTML 1.0 which released 2000 and HTML 5 which released 2000.
- Each HTML file should begin with **DOCTYPE** declaration to tell a browser which version of HTML the page is using.
- Comments are not visible for the user and they can be added between (<**!-- --**>). 
- ID attribute is used to uniquely identify that element from other elements on the page and it is global attribute because it can be used on any element.
- Class attributr is used to identify several elements.
- Block Level Elements: some elements will always appear to start on a new line in the browser window. 
- Inline Elements: Some elements will always appear to continue on the same line as their neighbouring elements. 
- An **iframe** is like a little window that has been cut into your page — and in that window you can see another page. 
- The **src** attribute specifies the URL of the page to show in the frame.
- The **height** attribute specifies the height of the iframe in pixels.
- The **width** attribute specifies the width of the iframe in pixels.
-  The **seamless** attribute does not need a value, but you will often see authors give it a value of seamless.
- The <**meta**> element lives inside the <**head**> element and contains information about that web page.
- Inside <**meta**> elements we can find some attributes with their contents such as:
   - **description** contains a description of the page.
   - **keywords** contains a list of commaseparated words that a user might search on to find the page. 
   - **robots** indicates whether search engines should add this page to their search results or not.
   - **author** defines the author of the web page.
   - **pragma** prevents the browser from caching the page.
   - **expires** it can be used to indicate when the page should expire.



### Extra Markup
- HTML5 introduces a new set of elements that allow you to divide up the parts of a page.
- The <**header**> and <**footer**> elements can be used for:
   - The main header or footer that appears at the top or bottom of every page on the site.
   - A header or footer for an individual <**article**> or <**section**> within the page.
- The <**nav**> element is used to contain the major navigational blocks on the site such as the primary site navigation.
- The <**article**> element acts as a container for any section of a page that could stand alone and potentially be syndicated.
- The <**aside**> element has two purposes, depending on whether it is inside an <**article**> element or not.
- The <**section**> element groups related content together, and typically each section would have its own heading.
- The <**hgroup**> element groups together a set of one or more <**h1**> through <**h6**> elements so that they are treated as one single heading.
- The <**figure**> contains any content that is referenced from the main flow of an article (not just images).
- The <**figcaption**> element which provides a text decription for the content of the <**figure**> element. 


### Process & Design
#### Steps to start designing a website.
- You should know who is the site for (**Target Audience**) are they individuals or Companies?
- Then, you should know why people visit your website because your content and design should be influenced by the goals of your users.
- Then, you should know what your visitors are trying to achieve.
- After that, you should decide what information your visitors need.
- Also, you should know how often people will visit your site.
- Then, you can start to organize the information into sections or pages.
- A **wireframe** is a simple sketch of the key information that needs to go on each page of a site.
- Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.
- Visual Hierarchy can get across your key message and help users find what they are looking for, because it refers to the order in which your eyes perceive what they see.
- You can use grouping and similarity to help simplify the information you present.
- You can differentiate between pieces of information using size, color, and style. 


# JavaScript

- **Script:** is a series of instructions that a computer can follow one-by-one.
- You need to state your goal and then list the tasks that need to be completed in order to achieve it.
- Steps to write a script:
   1. You need to define the task you want to achieve.
   2. Split the goal out into a series of tasks that are going to be used to achieve the goal.
   3. Each of the steps needs to be written in a programming language that the computer understands.
- Each programming language has its:
   - ***Vocabulary:*** The words that computers understand.
   - ***Syntax:*** How you put those words together to create instructions computers can follow. 
- ***Debbuging:*** the process of finding and resolving bugs within computer programs, software, or systems.
- **Objects:** in computer programming, each physical thing in the world can be represented as an object and each object can have its own properties, events and methods.
- **The Event:** is the computer's way of sticking up its hand to say, "Hey, this just happened!"
- **Methods:** represent how people interact with an object in the real world.
- Computers use data to create models of things in the real world. 
- The events, methods, and properties of an object all relate to each other.
- Using the document object, you can access and change what content users see on the page and respond to how they interact with it.

## ***How a browser sees a web page*** 
1. Recieving a page as HTML code.
2. Creating a model of the page and store it in memory.
3. Using a rendering engine to show the page on screen.

- All major browsers use a JavaScript interpreter to translate your instructions (in JavaScript) into instructions the computer can follow.
- There are three languages that are used to create web pages:
   - HTML
   - CSS
   - JavaScript 
- HTML file will be linked to CSS and JavaScript files.
- Each langaue of them form a layout, but each layout building depends on the previous one.
- HTML forms a ***content layout***.
- CSS forms a ***presentation layout***.
- JavaScript forms a ***behavior layout***.
- ***Progressive Enhancement:*** the basis of a popular approach to building web pages that formed by the three layouts.
- **HTML Only** focuses on the content only.
- **HTML+CSS** focuses on the content and how it will be displayed.
- **HTML+CSS+JAVASCRIPT** enhances the usability of the page.
- ***JavaScript File:*** it is a text file that ends with ".js".
- The HTML <**script**> element is used to load the JavaScript file into the page.
- ***document.write()*** writes content into the document.
   - document : represents the entire of a web page.
   - (.) : it is a member operator.
   - write(): it is a method with a parameter.

 


