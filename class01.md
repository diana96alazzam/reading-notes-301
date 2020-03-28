# Reading 1
## Article: Shay Howe’s intro to RWD

- What is the differnce between Responsive, Adaptive and Mobile design?
   * Responsive generally means to react quickly and positively to any change, With responsive design websites continually and fluidly change based on different factors, such as viewport width.

   * Adaptive means to be easily modified for a new purpose or situation, such as change. Adaptive websites are built to a group of preset factors.
   
   * Mobile, generally means to build a separate website commonly on a new domain solely for mobile users.

- What is the most popular technique nowadays?
  Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, responsive, adaptive, and mobile.

- What are the three main components of Responsive web design? 
  Flexible layouts
  Media queries.
  Flexible media.

- What are flexible layouts?
 Flexible layouts are the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width.
 
- What do we use to build Flexible grids?
 Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.


- What are the new relative length units, specifically related to the viewport size of the browser or device that CSS3 introduced?
  * vw: Viewports width.
  * vh: Viewports height.
  * vmin: Minimum of the viewport’s height and width.
  * vmax: Maximum of the viewport’s height and width.

- What is the formula that helps identifying the proportions of a flexible layout using relative values?
   **target ÷ context = result**
   It is based around taking the target width of an element and dividing it by the width of it’s parent element. The result is the relative width of the target element.

- What are Media queries?
  Media queries were built as an extension to media types commonly found when targeting and including styles. Media queries provide the ability to specify different styles for individual browser and device circumstances.

- What logical operators are used in Media queries?
   There are three different logical operators available for use within media queries, including:
   * and.
   * not.
   * only.

- Why do we use logical operators in media query and why?
  Using the and logical operator within a media query **allows an extra condition to be added**, making sure that a browser or devices does both a, b, c, and so forth. Multiple individual media queries can be comma separated, acting as an unspoken or operator.





## Article: All About Floats

- Floated elements remain a part of the flow of the web page.

- Absolutely positioned page elements are removed from the flow of the webpage and will not affect the position of other elements and other elements will not affect them, whether they touch each other or not.

- There are four valid values for the float property. 
  * **Left and Right**: float elements those directions respectively.
  * **None**: (the default) ensures the element will not float.
  * **Inherit**: which will assume the float value from that elements parent element.

- Floats can be used to create entire web layouts and also helpful for layout in smaller instances **BUT** these days, we have much stronger tools for creating layout on web pages. **Namely, Flexbox and Grid**. 

- Float's sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.

- Clear has four valid values as well:
  * **Both**: is most commonly used, which clears floats coming from either direction. 
  * **Left and Right**: can be used to only clear the float from one direction respectively. * **None**: is the default, which is typically unnecessary unless removing a clear value from a cascade.
  * **Inherit**: would be the fifth, but is strangely ***not supported*** in Internet Explorer.

- If parent element contained nothing but floated elements, the height of it would literally collapse to nothing. 

- We fix Collapsing by clearing the float after the floated elements in the container but before the close of the container.

- Techniques for Clearing Floats:
  * The Empty Div Method.
  * The Overflow Method.
  * The Easy Clearing Method.
  


# Skim
### Article: Don’t Overthink It Grids
### Article: CSS Floats Explained By Riding An Escalator - If you took Code 201, review this ### Article: article. If you did not take Code 201, this is Essential reading.

### Book: SMACSS Official Documentation