# Review, Research, and Discussion

### Why is the Context API useful?

The Context API can be used to share data with multiple components, without having to pass data through props manually.

### Can a component outside of a provider get its context?

no it can't because the provider send it's context to its child so if the component isn't child it can't get its context.

### What are some common use cases for using the Context API?



* Theming — Pass down app theme.

* i18n — Pass down translation messages.

* Authentication — Pass down current authenticated user.


### Describe “Context Hell”

When you have too many nested contexts… This is similar to callback hell. Can be addressed with the ‘React.cloneElement()’ function which returns a new element using the initial ‘element’ as a starting point.


term   |   Discripe
-| -
**global state** |  state which is declared at the app-level.
**global context** |  context hook which is visible to the entire app.
**Provider** |  The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider.
**consumer** |  React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.

### (DEFINITION OF ROLE-BASED ACCESS CONTROL)

 Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

### BENEFITS OF RBAC

* Reducing administrative work and IT support.

* Maximizing operational efficiency.

* Improving compliance.

