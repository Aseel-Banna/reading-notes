# EJS Partials
- Partials come in handy when you want to reuse the same HTML across multiple views.
- Partials are like the functions. 
- Partials make large websites easier to maintain, because you do not have to change for example a piece of text every page it appears in.
- You can define it in a separate file and include it where do you need it.
- Examples of partials to use same header and footer for all pages.
- The extension of these files will end with ***.ejs***.
- In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by ***<% %>*** delimiters, which means that you could change these delimiters if you really wanted to.
- The <%- %> tags allow us to output the unescaped content onto the page (notice the -). 
