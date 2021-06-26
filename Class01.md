

# **Introduction to React and Components**
![REACT](https://reactjs.org/logo-og.png)
# **Component-Based Architecture**

![component](https://www.techdiagonal.com/wp-content/uploads/2019/08/React-components-blog-image.jpg)


## **What is React?**
**Agnostic User Interface Library that means that we use it for creating user interfaces websites applications anything that the user is going to see in the browser and other places that react could go that is what it is primarily used to help with and the react has a component.**

## **What is a component?**
**A small piece of code that fills a certain part of the user interface that you are building with react.**


## **What is the dataflow of React?** 
**React has a one-way data flow which is becoming the standard today in JavaScript applications but it was one of the first to introduce it this is very different from two way binding which you maybe familiar with in JavaScript.**




## **What is a Component?**

*A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.*



## **What are the charactistics of a component?**

* Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

* Replaceable − Components may be freely substituted with other similar components.

* Not context specific − Components are designed to operate in different environments and contexts.

* Extensible − A component can be extended from existing components to provide new behavior.

* Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

* Independent − Components are designed to have minimal dependencies on other components.

## **What are the advantages of using component based architecture?**

* Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

* Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

* Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

* Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

* Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

* Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

* System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.

* Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

# **What is Props and How to Use it in React**

React has a different approach to data flow & manipulation than other frameworks, and that’s why it can be difficult at the beginning to understand some concepts like props, state and so on.


![PROPS](https://d2o2utebsixu4k.cloudfront.net/media/images/f3322bc4-a384-420a-8453-6654e2d4ff17.jpg)

## **What is props short for?**
“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

## **How are props used in React?**
1. Firstly, define an attribute and its value(data)
2. Then pass it to child component(s) by using Props
3. Finally, render the Props Data 

## **What is the flow of props?**
Props can only be passed to components in one-way (parent to child)

![DATAFLOW](https://miro.medium.com/max/700/1*3yqBUQ7qzBtlrXpUUhI1Dw.png)

## Conclusion
* Props are like parameters to a function  
* Props cannot be changed, they are immutable  
* A prop is a special keyword in React, that stands for properties  
* Props can only be passed in a uni-direction i.e (parent to child)  
* Props can be used to pass dynamic data to a component 
* A component re-renders when data in the props change  


 ## Things I want to know more about
 
I read some thing about state so i want to know what is the dufferent betwwen state and props .


### Sources:
* [A High Level Overview Of React](https://www.youtube.com/watch?v=FRjlF74_EZk)
* [Component](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)
* [React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)