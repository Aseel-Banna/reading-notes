# CSS 
### Images
- Images can describe the hole web page.
- Stock Images are images you pay to use.
- Images should be:
  - Be relevant.
  - Convey information.
  - Convey the right mood.
  - Be instantly recognisable.
  - Fit the color palette.
- You can store the images that you want to use inside your website in folder and subfolders.
- You can add an image using <**img**>.
- <**img**> is a self-closing tag.
- Image tag has attributes:
  - Source (*src*): to tell the browser where it can find the image file. You can even put the relative URL or the path.
  - Alternative Text (*alt*): to provide a text description of the image which describes the image if you cannot see it.
  - Title (*title*): to provide additional information about the image. 
  - Height(*height*): to specify the height of the an image in pixels.
  - Width (*width): to specify the width of the an image in pixels. 
  - Where an image is placed in the code it will affect how it is displayed.
- The browsers show HTML elements in two way:
  - Block elements always appear on a new line.
  - Inline elements sit within a block level element and do not start on a new line.
- The align attribute was commonly used to indicate how the other parts of a page should flow around an image.
- There are three main rules to use an image:
  - Save images in the right format.
  - Save images at the right size.
  - Use the correct resolution.
- Tools and Softwares that are used to edit images:
  - Adobe Photoshop
  - Adobe Fireworks
  - Pixelmator
  - PaintShop Pro
  - Paint.net
- Images created for the web should be saved at a resolution of 72 ppi. 
- Bitmap: images with format JPGs, GIFs, and PNGs.
- Vector images differ from bitmap images and are resolution-independent. 
- Animated GIFs show several frames of an image in sequence and therefore can be used to create simple  animations.
- <**figure**> element is introduced by HTML5 to contain images and their caption so that the two are associated. 
- The <figcaption> element has been added to HTML5 in order to allow web page authors to add a caption to an image.


### Colors
- Color is a property.
- Using ***color*** property, you can color any text element.
- You can use this property:
  - RGB Values: These express colors in terms of how much red, green and blue are used to make it up.
     - Values for red, green, and blue are expressed as numbers between 0 and 255.
     -  rgb(R,G,B).
  - HEX Values: Six-digit codes that represent the amount of red, green and blue in a color using hexadecimal code.
     - #000000.
  - Colors Names: There are 147 predefined color names that are recognized by browsers.
     - Red, Green, Black, White, ...etc.
  - HLSA: it is introduced by CSS3>
- CSS files allow you to add comments in your file either // for one line comment or /*...*/ for multilines comment.
- Comments are not presented in the browsers.
- Using comments can help you to understand the CSS file.

#### Background Color
- HTML elements appear as boxex in CSS file. 
- ***background-color*** is a property that sets the color of the background for the boxes.
- You can set this property as same as you set the ***color*** property.
- By default, the color of the browser's background is white.
- ***padding*** is a property that is used to separate the text from the edges of the boxes. 
- Every color on a computer screen is created by mixing amounts of red, green, and blue. 


- ***Pixels*** : are tiny squares that computers' monitor are made from.
- Each pixel can be a different color to create a picture.
- ***HUE***: it is a technically speaking  is the colloquial idea of color.
- A color can also have saturation and brightness as well as hue.
- ***Saturation*** it refers to the amount of gray in a color.
- ***Brightness*** (or "value") refers to how much black is in a color.
- ***Contrast*** it is divided for three parts:
  - Low Contrast: Text is harder to read when there is low contrast between background and foreground colors.
  - High Contrast: Text is easier to read when there is higher contrast between background and foreground colors.
  - Medium Contrast: For long spans of text, reducing the contrast a little bit improves readability.
- ***Lightness***: it is the amount of white (lightness) or black (darkness) in a color.

- ***Opacity*** it is a property which allows you to specify the opacity of an element and any of its child elements. 
- The value is a number between 0.0 and 1.0.
- ***rgba*** is a property that allows you to specify a color using alpha values.
- Alpha value: it is the fourth value of RGB value and it is a number between 0.0 and 1.0.
- RGBA they are values for red, green, blue and opacity.


### Texts
- Fonts:
  - Serif: Serif fonts have extra details on the ends of the main strokes of the letters. 
  - Sans-serif fonts have straight ends to letters, and therefore have a much cleaner design.
  - Monospace every letter in a monospace (or fixed-width) font is the same width.
  - Cursive fonts either have joining strokes or other cursive characteristics, such as handwriting styles.
  - Fantasy fonts are usually decorative fonts and are often used for titles.

- Weight:
  - Light
  - Medium
  - Bold
  - Black 

- Style:
  - Normal
  - Italic
  - Oblique

- Stretch
  - Condensed
  - Regular
  - Extended

- ***font-family***: it is a properity that the user's computer needs the typeface installed.
- ***font-face***: CSS specifies where a font can be downloaded from if it is not installed on the computer. 
- The ***font-size*** property enables you to specify a size for the font, usually measured by pixels, ems or percantage.
- ***@font-face*** allows you to use a font, even if it is not installed on the computer, by allowing you to
specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.
- ***src*** this specifies the path to the font. 
- ***format*** this specifies the format that the font is supplied in.
- The ***font-weight*** property allows you to create bold text.
- ***font-style*** allows the user to set the style either to italic or oblique.
- The ***text-transform*** property is used to change the case of text giving it one of the following values:
  - *uppercase* this causes the text to appear uppercase.
  - *lowercase* this causes the text to appear lowercase.
  - *capitalize* this causes the first letter of each word to appear capitalized.
- The ***text-decoration*** property allows you to specify the decoratine pof the text.
- The ***line-height*** property sets the height of an entire line of text, so the difference between the fontsize and the line-height is equivalent to the leading.
- The ***text-align*** property allows you to control the alignment of text.
- The ***vertical-align*** property is a common source of confusion. 
- The ***text-indent*** property allows you to indent the first line of text within an element.
- The ***text-shadow*** property has become commonly used despite lacking support in all browsers. 
- You can specify different values for the first letter or first line of text inside an element using
***:first-letter*** and ***:first-line***.
- ***:link*** this allows you to set styles for links that have not yet been visited.
- ***:visited*** this allows you to set styles for links that have been clicked on. 
- ***:hover*** this is applied when a user hovers over an element with a pointing device such as a mouse. 
- ***:active*** this is applied when an element is being activated by a user.
- ***:focus*** this is applied when an element has focus.


