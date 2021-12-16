# Review, Research, and Discussion

### When you have multiple contexts, what component type should you use (class/function) and why?

you can use both but but in class The static contextType property won't work if you need more than one, so instead you need to use a context consumer. 

### What are some good use cases for using the Context API for global state?

authuraization and user info  , becouse you need to check for these info in many componenet 

### How can you best test context?

The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).

term   |   Discripe
-| -
**context** |  context allows you to share information to any component, by storing it in a central place and allowing access to any child component
**useContext()** |  its a hook used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level.
**static context** |  its a method you can use it in the class component to use the global context.


### React.createContext 

       <MyContext.Provider value={/* some value */}>

Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

### Context.Provider

      <MyContext.Provider value={/* some value */}>

Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes.

All consumers that are descendants of a Provider will re-render whenever the Provider’s value prop changes. The propagation from Provider to its descendant consumers (including .contextType and useContext) is not subject to the shouldComponentUpdate method, so the consumer is updated even when an ancestor component skips an update.

