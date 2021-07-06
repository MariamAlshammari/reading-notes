## **Functional Programming **


## **1.What is functional programming?**

 ### functional programming is a programming paradigm where programs are constructed by applying and composing functions.When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects
 ![img](https://miro.medium.com/max/988/1*FcIxbMdz8KBfl6EKYsSQ5w.png)

## **2.What is a pure function and how do we know if something is a pure function?**

 ### pure function is a function that depends only on its declared inputs and its internal algorithm to produce its output. It does not read any other values from “the outside world” — the world outside of the function's scope — and it does not modify any values in the outside worls . SO , is a function where the return value is only determined by its input values, without observable side effects. This is how functions in math work: Math. cos(x) will, for the same value of x , always return the same result. Computing it does not change x .

 ![img1](https://cdn-media-1.freecodecamp.org/images/0*a_yub2gTwY-1eK8j.png)


## **3.What are the benefits of a pure function?**

 ### are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its 

## **4.What is immutability?**

### The value can not be changed. Once created a string object can not be modified as its immutable. If you request a substring of a string a new String with the requested part is created


## **5.What is Referential transparency?**

### this is what happens when you have pure functions and immutable data. So, for example, if one replaced a function with a number that the function would always result to, that would give it referential transparency.
### An expression in a program is said to be referentially transparent if it can be replaced with its value and the resulting behavior is the same as before the change.

![img2](https://image.slidesharecdn.com/taxonomy-of-scala-120924174954-phpapp01/95/taxonomy-of-scala-17-728.jpg?cb=1352313074)



# - **Videos**


## **1.What is a module?**

![img3](https://www.researchgate.net/publication/330344555/figure/fig2/AS:776707069988865@1562192804417/Components-of-a-module-in-an-information-system-application.png)


###  is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope.


## **2.What does the word ‘require’ do?**

### method is used to load and cache JavaScript modules. So, if you want to load a local, relative JavaScript module into a Node. js application, you can simply use the require() method.


## **3.How do we bring another module into the file the we are working in?**
### We use Require to point to a path to a js file. The .js ending is not necessary. e.g.–> require(./’count’); This is the first step in making that code able to function inside the module. Next, you have to make it available to use.

## **4.What do we have to do to make a module available?**

### The first thing you do to get access to module features is export them. This is done using the export statement.


## References:

* [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

* [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

