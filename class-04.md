### class-04

### *Links*
**Links are the defining feature of the web because they allow you to move from one web page to another enabling the very idea of browsing or surfing.**
- Writing Links
**Links are created using the *a* element. Users can click on anything between the opening *a* tag and the closing *a* tag. You specify which page you want to link to using the href attribute.**

![](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/06/Links-in-HTML.jpg)

- Linking to Other Sites
**Links are created using the *a* element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link**

- Linking to Other Pages on the Same Site
**When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL. If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file. If you have different pages of a site in different folders, then you can use a slightly more complex syntax to indicate where the page is in relation to the current page**

- Email Links
**mailto: To create a link that starts up the user's email program and addresses an email to a specified email address, you use the element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.**

- Opening Links in a New Window
**If you want a link to open in a new window, you can use the target attribute on the opening tag. The value of this attribute should be _blank.**

- Linking to a Specific Part of the Same Page
**At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top. Before you can link to a specific part of a page, you need to identify the points in the page that the link will go to. You do this using the id attribute (which can be used on every HTML element).**

- Linking to a Specific Part of Another Page
**If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique. As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page.**

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

* link: including multiple style sheets. Inside the *head* element is a separate *link* element for each style sheet.

### *Functions*
**Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).**

* Declaring a function
**To create a function you give it a name and then write the statement needed to achieve its task inside the curly braces(function declaration).**

![](https://i.stack.imgur.com/bCrSm.png)

* declaring functions with arguments:
![](https://cf.ppt-online.org/files/slide/z/ZQB7W6CTo0jgKzhF5VLlfNdbm1HPD2exvrSG9q/slide-27.jpg)

* Calling a function
**Having declared the function ,you can then execute all of the statement between its curly braces with just one line of code.**

![](https://i.ytimg.com/vi/95mIis5M-gU/hqdefault.jpg)

- VARIABLE SCOPE 
The location where you declare a variable will affect where it can be used  within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's scope. 
- HOW MEMORY & VARIABLES WORK 
Global variables use more memory. The browser has to remember them for as long as the web page using them is loaded. Local variables are only remembered during the period of time that a function is being executed. 

[Learn more about JS](https://www.w3schools.com/js/DEFAULT.asp)


* Functions allow you to group a set of related statements together that represent a single task.
* Functions can take parameters (informatiorJ required to do their job) and may return a value.
* An object is a series of variables and functions that represent something from the world around you.
* In an object, variables are known as properties of the object; functions are known as methods of the object.

#### *6 Reasons for Pair Programming*

* How does pair programming work?
**While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.**

* Why pair program?
**While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful**

**Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.**
1. Greater efficiency
**It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making. Research indicates that pair programing takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging (let alone exposing users to a broken product). So, in the long-run, it’s often actually more efficient than two people working on separate features.**

2. Engaged collaboration
**When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.**

3. Learning from fellow students
**Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of.**

4. Social skills
**Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key.**
**This has long-term career impacts. As much as employers want strong programmers, they know it’s essential to hire people who can work well with others.**

5. Job interview readiness
**A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. ​They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing so, companies can get a better feel for how an applicant will fit into the team and their collaboration style.**

6. Work environment readiness
**Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product.**





