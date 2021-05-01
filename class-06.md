##### class05
#### From the Duckett JS book

### WHAT IS AN OBJECT?
**Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.**

* *Creating an object literal notation*

- literal notation is the easiest and most popular way to create objects

![]( https://xomino.files.wordpress.com/2013/04/j1.png)
![]( https://image.slidesharecdn.com/oojs-1229037721986393-1/95/beginning-objectoriented-javascript-15-728.jpg?cb=1229139637)

- Accessing an object and dot notation
**You access the properties or method of an object using notation, also you access the properties using square brackets**

![]( https://i.stack.imgur.com/3uTtr.png)
![]( https://i.stack.imgur.com/ErYFs.png)

* *CREATING· OBJECTS USING LITERAL NOTATION*
![]( https://image.slidesharecdn.com/oojs-1229037721986393-1/95/beginning-objectoriented-javascript-15-728.jpg?cb=1229139637) 
![]( https://cdn.lynda.com/course/674601/674601-637491195140544626-16x9.jpg) 


### DOCUMENT OBJECT MODEL
**The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.**

**DOM trees have four types of nodes:**
1. document nodes
2. element nodes
3. attribute nodes
4. text nodes.

### *Caching DOM queries*
**Methods that find elements in the DOM tree are called DOM queries when you need to work with an element more than once, you should use a variable to store the result of this query.**

![]( https://images2.programmersought.com/258/99/99884f30dc77a62885b8e99cdc594d82.png)
![]( https://image.slidesharecdn.com/javascript-beyond-jquery-170923164633/95/javascript-beyondjquery-8-638.jpg?cb=1506185489)


### *ACCESSING ELEMENTS*

**DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.**

![]( https://assets.digitalocean.com/articles/eng_javascript/dom/html-rendering.png)

*Methods that select individual elements*

![]( https://www.codegrepper.com/codeimages/p-value-javascript.png)
![]( https://www.codegrepper.com/codeimages/how-to-select-class-with-queryselector.png)

#### *SELECTING ELEMENTS USING ID ATTRIBUTES*
*get El ementByi d () allows you to select a single element node by specifying the value of its id attribute.*

### *NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT*
**When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).**

* four different DOM queries that all return a Nodelist. For each query, you can see the elements and their index numbers in the Nodelist that is returned
  1- getElementsByTagName('hl ' )
  2- getElementsByTagName('li ')
  3- getElementsByClassName('hot')
  4- querySe l ectorA 11 ( ' l i [id] ' )

>An element node can contain multiple text nodes and child elements that are siblings of each other.

#### *SELECTING AN ELEMENT FROM A NODELIST*
**There are two ways to select an element from a Nodelist: The item() method and array syntax. Both require the index number of the element you want.**

#### *SELECTING ELEMENTS USING CLASS ATTRIBUTES*
**The get El ementsByCl ass Name() method allows you to select elements whose c 1 ass attribute contains a specific value.**

#### *SELECTING ELEMENTS BY TAG NAME*
**The get El ementsByTagName () method allows you to select elements using their tag name. The element name is specified as a parameter, so it is placed inside the parentheses and is contained by quote marks.**

#### *SELECTING ELEMENTS USING CSS SELECTORS*
**querySe 1 ector() returns the first element node that matches the CSS-style selector. querySe 1ectorA11 () returns a Nodelist of all of the matches. Both methods take a CSS selector as their only parameter.**

#### *LOOPING THROUGH A NODELIST* 
**If you want to apply the same code to numerous elements, looping through a Nodelist is a powerful technique. It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one.**

![]( https://res.cloudinary.com/practicaldev/image/fetch/s--niMLQyJZ--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/enr7lt657myo1m86bbjz.jpg)

### *TRAVERSING THE DOM*
**When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.**

1. parentNode
2. previousSibling 
3. nextSibling
4. firstChild
5. lastChild

#### *WHITESPACE NODES*
**Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.**

### *HOW TO GET/UPDATE ELEMENT CONTENT*
**JavaScript provides two properties, innerText and textContent, to get and set the text contents of an HTML element and all its child nodes .If you set a new value of innerText or textContent, all child nodes will be removed and replaced with a single text node containing the specified string.**

### *ACCESS & UPDATE TEXT WITH TEXTCONTENT (& INN ERTEXT)*
**The textContent property allows you to collect or update just the text that is in the containing element (and its children).**

#### *ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements.*

#### *ACCESS & UPDATE A TEXT NODE WITH NODEVALUE*
**When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property.**

#### *ACCESSING & CHANGI NG A TEXT NODE*
**To work with text in an element, first the element node is accessed and then its text node. JAVASCRIPT The text node has a property called node Value which returns the text in that text node.**

#### *ACCESSING TEXT ONLY*

![](v https://i.stack.imgur.com/N1odX.png)

#### *ADDING ELEMENTS USING DOM MANIPULATION* 
**DOM manipulation offers another technique to add new content to a page (rather than i nnerHTML). It involves three steps:**
1. CREATE THE ELEMENT createEl ement ()
2. GIVE IT CONTENT createTextNode()
3. ADD IT TO THE DOM appendChild()

#### *REMOVING ELEMENTS VIA DOM MANIPULATION*
**DOM manipulation can be used to remove elements from the DOM tree.**

#### *UPDATING HTML CONTENT* 
**So far, you have seen three techniques for adding HTML to a web page. It's time to compare when you should use each one.**
1. document.write()
2. element.innerHTML
3. DOM MANIPULATION

### *CROSS-SITE SCRIPTING (XSS) ATTACKS*
**If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts.**

### *CREATING ATTRIBUTES & CHANGING THEIR VALUES*
**The className property allows you to change the value of the cl ass attribute. If the attribute does not exist, it will be created and given the specified value.**

#### *REMOVING ATTRI BUTES*
**To remove an attribute from an element, first select the element, then call removeAtt r i bute () . It has one parameter: the name of the attribute to remove.**

> EXAM INING THE DOM IN CHROME Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree.
> EXAMINING THE DOM IN FIREFOX Firefox has similar built-in tools, but you can also download a DOM inspector tool that shows the text nodes.