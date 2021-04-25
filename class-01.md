#### class-01

### Introduction

### *How the Web Works*
**When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server**

### *Structure*
#### HTML Uses Elements to Describe the Structure of Pages
**Let's look closer at the code from the last page. 
There are several different elements. Each 
element has an opening tag and a closing tag.**
![](https://www.w3schools.com/html/img_notepad.png)
- *Tags act like containers. They tell you something about the information that lies between their opening and closing tags*
- Tags usually come in pairs. The opening tag denotes 
the start of a piece of content; the closing tag denotes 
the end.
![img2](https://hi-static.z-dn.net/files/d72/7fa73ad3345012d066f693a8d5b3e83d.jpg)

#### *Attributes Tell Us More About Elements*

Opening tags can carry attributes, which tell us more 
about the content of that element.
- Attributes require a name and a value.


![](https://www.computerhope.com/jargon/h/html-tag.gif)

### *Extra Markup*
* >Because there have been several versions of HTML, each 
web page should begin with a DOCTYPE declaration to tell a 
browser which version of HTML the page is using (although 
browsers usually display the page even if it is not included). 
* Comments in HTML: <!-- -->
* ID Attribute:Every HTML element can carry the id attribute. It is used to uniquely identify that element 
from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character).
* Class Attribute:Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. 
* Block Elements:Some elements will always appear to start on a new line in the browser window. These are known as block level elements. 
* Inline Elements: Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements. 
* The <div> and <span> elements allow you to group 
block-level and inline elements together.
* <iframes> cut windows into your web pages through 
which other pages can be displayed.
* The <meta> tag allows you to supply all kinds of 
information about your web page.
* *Escape Characters*
**There are some characters that are used in 
and reserved by HTML code. (For example, the 
left and right angled brackets.)**
![](https://i.pinimg.com/originals/e9/06/5f/e9065fb4413e79caec092dbc14e1a6cf.jpg)


### *HTML5 Layout*
**HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already.**

* *Headers & Footers <header> <footer>:The <header> and <footer> elements can be used for:*
  * *The main header or footer that appears at the top or  bottom of every page on the site.*
  * *A header or footer for an individual <article> or <section> within the page.*
* Navigation *<nav>*:The *<nav>* element is used to contain the major navigational blocks on the site such as the primary site navigation
* Articles *<article>* :The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.
* Article:The *<aside>* element has two purposes, depending on whether it is inside an *<article>* element or not.
* Sections:The *<section>* element groups related content together, and typically each section would have its own heading.
* The *<section>* element groups related content together, and typically each section would have its own heading.
* Figures:You already met the *<figure>* element in Chapter 5 when we looked at images. It can be used to contain any content that is referenced from the main flow of an article (not just images). 

![](https://images.slideplayer.com/24/7231201/slides/slide_4.jpg)

* To make HTML5 elements work in Internet Explorer 8 
(and older versions of IE), extra JavaScript is needed, 
which is available free from Google.


### *Process & Design*
1. Who is the Site For?
**Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.**

2. Why People Visit YOUR Website
To help determine why people are coming to your website, 
there are two basic categories of questions you can ask:
   1. The first attempts to discover the underlying motivations for why visitors come to the site.
   2. The second examines the specific goals of the visitors. These are the triggers making them come to the site now

3. What Your Visitors are Trying to Achieve: It is unlikely that you will be able to list every reason why someone visits your site but you are looking for key tasks and motivations.

### *Site maps allow you to plan the structure of a site.*
![site maps](https://www.connectinternetsolutions.com/wp-content/uploads/2016/03/html-sitemap.png)

### *Wireframes allow you to organize the information that will need to go on each page.*
![wireframes](https://i.pinimg.com/originals/c3/de/24/c3de24c8c79004b349f12052f76d70b0.png)

### Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.

### *Visual hierarchy*
**Most web users do not read entire pages. Rather, they skim to find information. You can use contrast to create a visual hierarchy that gets across your key message and helps users find what they are looking for.**
* You can differentiate between pieces of information 
using size, color, and style. 
* You can use grouping and similarity to help simplify 
the information you present.

### introduction for JS:
**BEHAVIOR LAYER *.js* files This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files.
Create a folder to put the example in called cOl, then start up your favorite code editor, and enter the text to the right. A JavaScript file is just a text file (like HTML and CSS files are) but it has a . j s file extension, so save this file with the name add-content . j s**

### *The ABC of Programming*
#### A script

- When you want to use JavaScript with a web page, you use the HTML
**The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file).
If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.**
- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

### *COMPUTERS CREATE MODELS OF THE WORLD USING DATA*
* *OBJECTS & PROPERTIES*
**In computer programming, each physical thing in the world can be represented as an object.
Each object can have its own: **
* Properties 
* Events:In the real world, people interact with objects. These interactions can change the values of the properties in these objects.  
* Methods: Methods represent things people need to do with objects. They can retrieve or update the values of an object's properties.  
**Together they create a working model of that object.PUTTING IT ALL TOGETHER Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an objects properties.  **
* THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE Using the document object, you can access and change what content users see on the page and respond to how they interact with it.
* HOW A BROWSER SEES A WEB PAGE?
1.  RECEIVE A PAGE AS HTML CODE 
2. CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY.
3. USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN.

### *How do i write a script for a web page?*

* It is best to keep JavaScript code in its own JavaScript  file. JavaScript files are text files (like HTML pages and  CSS style sheets), but they have the . j s extension. 
* The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).
* If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created. 

### *Objects & Methods*

![Objects & Methods](https://media.geeksforgeeks.org/wp-content/uploads/20190306104652/obj21.png)

![Objects & Methods2](https://i.stack.imgur.com/PpIXb.jpg)




