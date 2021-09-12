## What types of things can you pass in the props?

* props enable you to pass variables from one to another component down the component tree also props can be anything from integers over objects to arrays.

## What is the big difference between props and state?

* The key difference between props and state is that state is internal and controlled by the component itself while props are external and controlled by whatever renders the component.

## When do we re-render our application?

* React components automatically re-render whenever there is a change in their state or props. 

## What are some examples of things that we could store in state?

* Some users prefer to keep every single piece of data in Redux, to maintain a fully serializable and controlled version of their application at all times. Others prefer to keep non-critical or UI state, such as “is this dropdown currently open”, inside a component's internal state. Using local component state is fine.

## What is the very first thing to happen in the lifecycle of React?

* The static getDerivedStateFromProps is the first React lifecycle method to be invoked during the updating phase.

## What does componentDidMount do?

* The componentDidMount() method allows us to execute the React code when the component is already placed in the DOM (Document Object Model). This method is called during the Mounting phase of the React Life-cycle i.e after the component is rendered.

## What happens first, the ‘render’ or the ‘componentDidMount’?

* When a component is mounted it is being inserted into the DOM. This is when a constructor is called. componentWillMount is pretty much synonymous with a constructor and is invoked around the same time. componentDidMount will only be called once after the first render.

## Things I want to know more about
