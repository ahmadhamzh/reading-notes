# Review, Research, and Discussion

### How can we ensure that an effect hook runs only once?

If you only want to run the function given to useEffect after the initial render, you can give it an empty array as second argument. useEffect(yourCallback, []) - will trigger the callback only after the first render.

### Can useState() update more than one state variable at the same time?

To update the component's state invoke the updater function setState(newState) with the new state. The component re-renders and state receives the new value newState.,Invoking the state updater function setState(newState) with the new value updates the state.

### Is useState() synchronous?

useState and setState both are asynchronous.,They do not update the state immediately but have queues that are used to update the state object.

term   |   Discripe
-| -
**State Hook** |  A Hook is a special function that lets you “hook into” React features.
**Component Lifecycle** |  Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM).


##  useReducer

useReducer is one of the additional Hooks that shipped with React 16.8. An alternative to the useState Hook, it helps you manage complex state logic in React applications. When combined with other Hooks like useContext, useReducer can be a good alternative to Redux or MobX — indeed, it can sometimes be an outright better option.

### How does useReducer work?

useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second.

### The reducer function

The reduce() method in JavaScript executes a reducer function on each element of the array an and then returns a single value. The reduce() method accepts a reducer function, which itself can accept up to four arguments.

