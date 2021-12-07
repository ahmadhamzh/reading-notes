# Review, Research, and Discussion

### Why do we not need more .html pages in a multi-page React app?

because react useing Router and it's a great way to build single-page applications because you prevent a page refresh every time a link is clicked. With client-side rendering, the page doesn't refresh as you navigate through the different links. React Router is easy to understand, and simple to implement

### If we wanted a component to show up on every page, where would we put it and why?

Inside the <BrowserRouter , outside a <Route becase we want the component to be shoen inside the brwoser but in all routes so if routes change the commponent won't gone becasue it's out of routes 

### What does routing do with the components that were rendered when a new route is requested?

when routs changing the components that belong to the rout that match with the url will be render and the other components will not be render 

### What does props.children contain?

it contain all the data that you pass it from the parents to the childes

### How do useState() and this.setState() differ?

Unlike the setState method found in class components, useState does not automatically merge update objects.


term   |   Discripe
-| -
**State Hook** |  A Hook is a special function that lets you “hook into” React features.
**Mounting and Un-Mounting** |  "mounting" (adding nodes to the DOM), "unmounting" (removing them from the DOM),

### Using the Effect Hook

* Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class.

* **What does useEffect do?** : By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.

* **Why is useEffect called inside a component?**
Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don’t need a special API to read it — it’s already in the function scope. 


* **Does useEffect run after every render?** Yes! By default, it runs both after the first render and after every update.

* **Why did we return a function from our effect?**This is the optional cleanup mechanism for effects. Every effect may return a function that cleans up after it. This lets us keep the logic for adding and removing subscriptions close to each other. 

* **When exactly does React clean up an effect?** React performs the cleanup when the component unmounts. However, effects run for every render and not just once. This is why React also cleans up effects from the previous render before running the effects next time. 