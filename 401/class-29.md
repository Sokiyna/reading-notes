# Advanced State with Reducers

## Review, Research, and Discussion

How can we ensure that an effect hook runs only once?

If we pass an empty array [] , it just renders the component only once like componentDidMount .

Can useState() update more than one state variable at the same time?

You could combine the state into one state object and then you could do one setState call and there will only be one render. Unlike the setState in class components, the setState returned from useState doesn’t merge objects with existing state, it replaces the object entirely.

  const [form, setState] = useState({
    username: '',
    password: ''
  });

Is useState() synchronous?

useState and setState both are asynchronous. Even though they are asynchronous, the useState and setState functions do not return promises. Therefore we cannot attach a then handler to it or use async/await to get the updated state values.


### Terms

**State Hook**

The useState() is a Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries.

**Component Lifecycle**

the series of methods that are invoked in different stages of the component’s existence. The three phases are: Mounting, Updating, and Unmounting.

## Preparation Materials


#### useReducer is one of the additional Hooks that shipped with React 16.8. An alternative to the useState Hook:

it helps you manage complex state logic in React applications.
useReducer can be a good alternative to Redux or MobX — indeed,
it can sometimes be an outright better option. useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

#### There are three main building blocks in Redux:

A store — an immutable object that holds the applications state data
A reducer — a function that returns some state data, triggered by an action type
An action — an object that tells the reducer how to change the state. It must contain a type property, and it can contain an optional payload property