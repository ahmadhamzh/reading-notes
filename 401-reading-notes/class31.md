# Review, Research, and Discussion

### Describe use cases useState() vs useReducer() ?

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

### Why do custom hooks need the use prefix?

Custom hooks are normal JS functions, named with the prefix 'use', that can use hooks inside of it and contain a common stateful logic to be reused in other components.

### What do custom hooks usually do?

allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.

### Using any list of custom hooks, research and name one that you think will be useful in your applications

useOnClickOutside : This hook allows you to detect clicks outside of a specified element.

### reducer 

reducer is a function which takes two arguments — the current state and an action — and returns based on both arguments a new state.


### Context

 * Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

* Context is primarily used when some data needs to be accessible by many components at different nesting levels.

* Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

* Context.Consumer : A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.

* Context.displayName : Context object accepts a displayName string property. React DevTools uses this string to determine what to display for the context.

----
**refrences** : 
 
 * [context api](https://reactjs.org/docs/context.html)