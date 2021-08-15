# Context API - Behaviors
 
 ## Review, Research, and Discussion

#### When you have multiple contexts, what component type should you use (class/function) and why?

The difference is pretty obvious. Class components are ES6 classes and Functional Components are functions. The only constraint for a functional component is to accept props as an argument and return valid JSX.

#### What are some good use cases for using the Context API for global state?

Twilio : Twilio really defines what it means to be API-driven.
Stripe : Stripe is one of the most successful and best known API-driven businesses.
Ebay : Unlike the previous companies, eBay didn’t start out with the intent of being API-driven.
Salesforce : XML APIs have been a part of Salesforce since day one, back in 2000 when it launched.
Rovi :Rovi is definitely the oldest company on the list, founded as Macrovision in 1983.

#### How can you best test context?

The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).

# Terms

**context :** Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

**useContext() :** hook is used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level. Context defined will be available to all the child components without involving “props”.

**static context :** If you are using the experimental public class fields syntax, you can use a static class field to initialize your contextType.

## Api

**React.createContext**
Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

The defaultValue argument is only used when a component does not have a matching Provider above it in the tree. This default value can be helpful for testing components in isolation without wrapping them. Note: passing undefined as a Provider value does not cause consuming components to use defaultValue.

**Context.Provider**

All consumers that are descendants of a Provider will re-render whenever the Provider’s value prop changes. The propagation from Provider to its descendant consumers (including .contextType and useContext) is not subject to the shouldComponentUpdate method, so the consumer is updated even when an ancestor component skips an update.

Changes are determined by comparing the new and old values using the same algorithm as Object.is.

**Context.Consumer**

A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.

Requires a function as a child. The function receives the current context value and returns a React node. The value argument passed to the function will be equal to the value prop of the closest Provider for this context above in the tree. If there is no Provider for this context above, the value argument will be equal to the defaultValue that was passed to createContext().


