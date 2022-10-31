# Reading
## React lifecycle

1) Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render


2) What is the very first thing to happen in the lifecycle of React?

    Constructor


3) Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

 constructor, render, componentDidMount, componentWillUnmount, React updates

4) What does componentDidMount do?

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. 


![React Lifecycle0](./reactLifecycle.PNG)

# Videos
## React State Vs Props

1) What types of things can you pass in the props?

* Counter
* Display something to the user with a title or subtitle

2) What is the big difference between props and state?

prop it used to pass a component and it updated outside the component, but state it existing inside the component and is updated inside it.

3) When do we re-render our application?

We can re-render our application when we change the state.
When we want to update our application we should store the updated part inside a state, to re-render it.

4) What are some examples of things that we could store in state?
* Counter
* Select box
* Check box