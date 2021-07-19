# State and Props

## [React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

* render

2. What is the very first thing to happen in the lifecycle of React?

* Constructor

3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

* `constructor`, `render`, `React Updates`, `componentDidMount`, `componentWillUnmount`

4. What does componentDidMount do?

*  method invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here

## [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. What types of things can you pass in the props?

* things you pass to the constructor of that class

2. What is the big difference between props and state?

* state is inside a component, props you pass into the component but handled outside the component

3. When do we re-render our application?

* change the state

4. What are some examples of things that we could store in state?

* when you want to change something 