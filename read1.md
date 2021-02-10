# Responsive Web Design
- Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
- Responsive and adaptive web design are closely related, and often transposed as one in the same. 
- Responsive means to react quickly and positively to any change, while adaptive means to be easily modified for a new purpose or situation, such as change. 
- Responsive design websites continually and fluidly change based on different factors, such as viewport width.
- Adaptive websites are built to a group of preset factors. 
- A combination of the two is ideal, providing the perfect formula for functional websites. 
- Mobile means to build a separate website commonly on a new domain solely for mobile users. 
- Favoring design is the most popular technique lies within responsive web design that dynamically adapts to different browser and device viewport, changing layout and content along the way.
- Responsive web design is broken down into three main components:
  1. Flexible layouts.
  2. Media queries.
  3. Flexible media.  
- Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches.
- Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units.
- Taking the flexible layout concept, and formula, and reapplying it to all parts of a grid will create a completely dynamic website, scaling to every viewport size. 
- Media queries were built as an extension to media types commonly found when targeting and including styles. 
- There are a couple different ways to use media queries, using the ***@media*** rule inside of an existing style sheet, importing a new style sheet using the ***@import*** rule, or by linking to a separate style sheet from within the HTML document. 
- There are three different logical operators available for use within media queries ***and, not, and only***.
- The **min** and **max** prefixes can be used on quite a few media features. 
- The orientation media feature determines if a device is in the landscape or portrait orientation. 
- The *aspect-ratio* and *device-aspect-ratio* features specifies the width/height pixel ratio of the targeted rendering area or output device. 
- The value for the aspect ratio feature consist of two positive integers separated by a forward slash.
- The **resolution** media feature specifies the resolution of the output device in pixel density, also known as ***dots per inch*** or ***DPI***. 
- The **mobile first** approach includes using styles targeted at smaller viewport as the default styles for a website, then use media queries to add styles as the viewport grows.
- The mobile first approach also advocates designing with the constraints of a mobile user in mind. Before too long, the majority of Internet consumption will be done on a mobile device. 
- Using the viewport meta tag with either the height or width values will define the height or width of the viewport respectively.
- To control how a website is scaled on a mobile device, and how users can continue to scale a website, use the minimum-scale, maximum-scale, initial-scale, and user-scalable properties.
- As viewport begin to change size media doesn’t always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.


# What is “Float”?
- Float is a CSS positioning property. 
- Absolutely positioned page elements will not affect the position of other elements and other elements will not affect them, whether they touch each other or not.
- There are four valid values for the float property:
  - Left and Right float elements those directions respectively.
  - None (the default) ensures the element will not float.
  - Inherit which will assume the float value from that elements parent element.
- Aside from the simple example of wrapping text around images, floats can be used to create entire web layouts.
- Floats are also helpful for layout in smaller instances.
- Clear has four valid values. 
  - Both is most commonly used, which clears floats coming from either direction. 
  - Left and Right can be used to only clear the float from one direction respectively.
  - None is the default, which is typically unnecessary unless removing a clear value from a cascade.
  - Inherit would be the fifth, but is strangely not supported in Internet Explorer. 
- Techniques for Clearing Floats
  - The Empty Div Method
  - The Overflow Method
  - The Easy Clearing Method 
- Problems with Floats
  - **Pushdown** is a symptom of an element inside a floated item being wider than the float itself (typically an image). 
  - **Double Margin Bug** – Another thing to remember when dealing with IE 6 is that if you apply a margin in the same direction as the float, it will double the margin.
  - The **3px Jog** is when text that is up next to a floated element is mysteriously kicked away by 3px like a weird forcefield around the float. 
  - The **Bottom Margin Bug** is when if a floated parent has floated children inside it, bottom margin on those children is ignored by the parent. 


  # Don’t Overthink It Grids
  - Context: A block level element is as wide as the parent it’s inside (width: auto;).
  - The wrapper for a grid probably don’t have much to do with semantics, it’s just a generic wrapper, so a div is fine.
  - Columns: set the width of the columns.
  - Clearing Context: The parent element will collapse to zero height since it has only floated children.
  - Gutters: The hardest part about grids is gutters. 
  
  # SMACSS is becoming one of the most useful contributions to front-end discussions in years
  - SMACSS is more style guide than rigid framework. 
  - SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process.
  