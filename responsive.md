# Regular expressions
- Regular expressions is used to extract information from any text by searching for one or more matches of a specific search pattern.
- You can use this feature in all programming languages.
- You can use:
  - Anchors — ^ and $
  - Quantifiers — * + ? and {}
  - OR operator — | or []
  - Character classes — \d \w \s and .
- g (global) does not return after the first match, restarting the subsequent searches from the end of the previous match
- m (multi-line) when enabled ^ and $ will match the start and end of a line, instead of the whole string
- i (insensitive) makes the whole expression case-insensitive (for instance /aBc/i would match AbC)
- Intermediate topics:
  - Grouping and capturing — (): it is very useful when we need to extract information from strings or data using your preferred programming language.
  - Bracket expressions — []
  - Greedy and Lazy match: if you want to catch only element itself, you can use a ***?*** to make it lazy.
- Advanced topics:
  - Boundaries — \b and \B
  - Back-references — \1
  - Look-ahead and Look-behind — (?=) and (?<=)


# A Complete Guide to Grid
- CSS Grid Layout is a 2-d system, where flexbox is 1-d.
- The history of grid came with this order: tables, then floats, positioning and inline-block.
- To use grid in a container, you have to set display: grid, set the column and row sizes with grid-template-columns and grid-template-rows, and then place its child elements into the grid with grid-column and grid-row.
- We have Grid Container, Grid Item, Grid Line, Grid Cell, Grid Track and Grid Area as properties of grid layout.
- Properties for the Grid Container:
  - display
  - grid-template-columns
  - grid-template-rows
  - grid-template-areas
  - grid-template
  - grid-column-gap
  - grid-row-gap
  - grid-gap
  - justify-items
  - align-items
  - place-items
  - justify-content
  - align-content
  - place-content
  - grid-auto-columns
  - grid-auto-rows
  - grid-auto-flow
  - grid
- Properties for the Grid Items
  - grid-column-start
  - grid-column-end
  - grid-row-start
  - grid-row-end
  - grid-column
  - grid-row
  - grid-area
  - justify-self
  - align-self
  - place-self

- All of these properties control how the grid layout will be displayed.


# Common Responsive Layouts with CSS Grid (and some without!)
- CSS grid allows us to arrange elements in multiple rows and columns.
- The repeat() function takes two arguments, the first will define the number of column tracks and the second, what width the tracks should be.
- Using auto-fill will create a grid with as many tracks as will fit into the container.
- The minmax function will create track widths. 
- fr is a ‘fraction unit’.
- grid-gap property defines the size of the space between the columns and the rows.
