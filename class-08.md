### *Layout*
- Key Concepts in Positioning Elements
**Building Blocks CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.**
**Containing Elements If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.**

- Controlling the Position of Elements
 **CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.**
**To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed.**
   - Normal Flow: in normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be: position: static; I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default
  - Relative Positioning: Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right. You can indicate that an element should be relatively positioned using the position property with a value of relative.
  ![](https://miro.medium.com/max/2764/1*KZ-8SET0HK5j9V1pxT_5mw.png)

  - Absolute Positioning: When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) The box offset properties (top or bottom and left or right) specify where the element should appear in relation to its containing element.

  - Fixed Positioning: Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.

  - Overlapping Elements z-index :When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.

  - Floating Elements: The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated.

- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)



##### *Layouts*
* Fixed Width Layouts
**Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.**

* Pages can be fixed width or liquid (stretchy) layouts. 
* Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

* A Fixed Width Layout
**To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels (and sometimes their height, too)**


* Layout Grids:
**Composition in any visual art (such as design, painting, or photography) is the placement or arrangement of visual elements — how they are organized on a page. Many designers use a grid structure to help them position items on a page, and the same is true for web designers**
* Grids help create professional and flexible designs.

#### *Screen Sizes*
**Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens**

![](https://allma.si/blog/wp-content/uploads/2020/09/display-different-images-based-on-screen-size.png)

* Screen Resolution
**Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.**

* Page Sizes
**Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).**

### *Multiple Style Sheets*
**@import :Some web page authors split up their CSS style rules into separate style sheets. For example, they might use one style sheet to control the layout and another to control fonts, colors and so on. Some authors take an even more modular approach to stylesheets, creating separate stylesheets to control typography, layout, forms, tables, even different styles for each sub-section of a site.**


* The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.) 
* Pages can be fixed width or liquid (stretchy) layouts. 
* Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling). 
* Grids help create professional and flexible designs.