# Transforms
- The size, position, and change elements are made possible by the **transform** property.
- The **transform** property comes in two different settings, ***two-dimensional and three-dimensional***. 
- The actual syntax for the **transform** property is quite simple, including the **transform** property followed by the value.

### 2D Transforms
- Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. 
- Three-dimensional transforms work on both the x and y axes, as well as the z axis and these help define not only the length and width of an element, but also the depth. 
- The transform property accepts a handful of different values. 
- The rotate value provides the ability to rotate an element from 0 to 360 degrees.
- Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
- The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically. 
- Using the scale value within the transform property allows you to change the appeared size of an element. 
- It is possible to scale only the height or width of an element using the scaleX and scaleY values.
- The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
- The last transform value in the group, **skew**, is used to distort elements on the horizontal axis, vertical axis, or both. 
- The distance calculation of the skew value is measured in units of degrees.
- To combine transforms, list the transform values within the transform property one after the other without the use of commas.
- To change default origin position the transform-origin property may be used.
- The transform-origin property can accept one or two values. 
- The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.
- Using the perspective value within the transform property works great for transforming one element from a single, unique perspective.
- The perspective value can be set as none or a length measurement.
- he same values used for the transform-origin property may also be used with the perspective-origin property, and maintain the same relationship to the element. 


# Transitions
- The easiest way for determining styles for different states is by using the ***:hover, :focus, :active, and :target*** pseudo-classes.
- There are four transition related properties in total, including ***transition-property, transition-duration, transition-timing-function, and transition-delay.***
- The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. 
- Not all properties may be transitioned, only properties that have an identifiable halfway point.
- The transition-timing-function property is used to set the speed in which a transition will move.
- The linear keyword value identifies a transition moving in a constant speed from one state to another. 
- On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property. 
- The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. 
- Using the transition value alone, you can set every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay.
- When more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.
- It is important to note, as with transitions only individual properties may be animated.
- The animation-name declaration is applied to the element in which the animation is to be applied to.
- The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively.
- The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run. 


# 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
1. Fade in
- It’s a great way to emphasize functionality or draw attention to a call to action.
- Fade in effects are coded in two steps: first, you set the initial state; next, you set the change.

2. Change color
- Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them. 

3. Grow & Shrink
- To grow an element, you used to have to use its width and height, or its padding.
- To enlarge an element we specify a value greater than 1, to shrink it, we specify a value less than 1.

4. Rotate elements
- CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.

5. Square to circle
- A really popular effect at the moment is transitioning a square element into a round one, and vice versa. 

6. 3D shadow
- This effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen.

7. Swing 
- Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.

8. Inset border
- One of the hottest button styles right now is the ghost button; a button with no background and a heavy border.

