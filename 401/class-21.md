# Component Based UI

### Name 5 Javascript UI Frameworks (other than React)?

Angular
Vue.js
jQuery
Backbone.js
Polymer

### What’s the difference between a framework and a library?

A library is essentially a set of functions that you can call, these days usually organized into classes. Each call does some work and returns control to the client.
A framework embodies some abstract design, with more behavior built in. In order to use it you need to insert your behavior into various places in the framework either by subclassing or by plugging in your own classes. The framework's code then calls your code at these points.

## Terms

Rendering:

Rendering is a process that is triggered by a change of state in some component of your application, when a state change occurs React: It will collect from the root of your App all the components that requested a re-render because their state or their props changed.

Templates:

React templates are sets of ready-to-use parts of code built using React technology for the development of dynamic user interfaces. React templates may contain full-fledged pages with a pre-built design, component compositions, stand-alone components, styling (like fonts, colors theme effects, background styles, icons), plugins, widgets, libraries

State:

What is State? The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

### What Is React?

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

### what is JSX?

JSX stands for JavaScript XML. It is simply a syntax extension of JavaScript. It allows us to directly write HTML in React (within JavaScript code). It is easy to create a template using JSX in React, but it is not a simple template language instead it comes with the full power of JavaScript.

## Preparation Materials

JSX is syntax extension to JavaScript and produces React “elements”.

JSX is used to create both markups and logics with one kinda language.

ex)


const name = 'Josh Perez';
const element = <h1>Hello, {name}</h1>;

ReactDOM.render(
  element,
  document.getElementById('root')
);

In the example above name, which is inside the curly brackets can be any valid JS expression. It can be a function, object, mathematical operation…etc.

JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects. That means it can be used in many methods, like if statements, for loops, assigned in variables …etc.

You can set attributes by using either quotes or curly braces, but nit both at the same time.

const element = <div tabIndex="0"></div>;

const element = <img src={user.avatarUrl}></img>;
By default, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.
rendering elements
Elements are the smallest building blocks of React apps.

Unlike browser DOM elements, React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements.

Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

To update the rendered element in react, you have to add a new element.

React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.