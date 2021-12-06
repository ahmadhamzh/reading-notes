# Review, Research, and Discussion

### How does React differ from vanilla JS/HTML/CSS?


- JS requires a lot of codes so would be little messy and that make it less efficient than React.

-  Vanilla JS is fragile

- ReactJs is great for organizing the code.

-  React JS files are reusable


### What is the primary difference between a function component and a class component?

functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.


term   |   Discripe
-| -
**Functional Components** |  functional component is just a plain JavaScript function that accepts props as an argument and returns a React element.
**Children / Child Components** |  its a props in react allow you to pass components as data to other components,

### hooks 

 * **What is a Hook?** : Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components. We’ll learn other Hooks later.

 * **When would I use a Hook?** : If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component. We’re going to do that right now!

 * **Declaring a State Variable** :

   * in class componenet :

         class Example extends React.Component {
          constructor(props) {
           super(props);
            this.state = {
             count: 0
           };
         }

    * in function componenet : 

          import React, { useState } from 'react';

          function Example() {
           // Declare a new state variable, which we'll call "count"
           const [count, setCount] = useState(0); 

* **the  Effect Hook :**

   useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API.

* **Hooks are JavaScript functions, but they impose two additional rules :** 

   * Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.

   * Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.

   ---
 ## refrences : 

 * [making sense of hooks](https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889)
  * [the state hook](https://reactjs.org/docs/hooks-state.html)
 * [hooks api](https://reactjs.org/docs/hooks-overview.html)
 * [hooks api reference](https://reactjs.org/docs/hooks-reference.html)