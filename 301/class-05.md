1- we should draw boxes around every component and also subcomponent in the mock and give them all names.

2- a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

3- The components will only have render() and no interactivity.

4- you should add State to make the UI interactive.

5- Is it passed in from a parent via props? If so, it probably isn’t state.
Does it remain unchanged over time? If so, it probably isn’t state.
Can you compute it based on any other state or props in your component? If so, it isn’t state.

6- Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.