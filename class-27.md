# Class 27 Reading Notes

## Thinking in React

1. Summarize the five steps of thinking in react.

- Break the UI into a component hierarchy, create a layout or design of how you want your app to look
- Build a static version in React, make data model with no interaction
- Find the minimal but complete representation of UI state, use state and determine waht won't need state.
- Identify where your state should live, which component should the state be in.
- Add inverse data flow, to be able to change state based on user input.

## State: A Component’s Memory

1. What is one reason a local variable isn’t sufficient for managing a React component?
  Local variables will not persist between different renders.

2. What is the argument to the useState hook, and what are the two parts of its return array?
  `use` it will return a state variable that can stay existing between different renders and it will get a state setter function that will update this variable in state if needed and trigger another render on this component again.

3. How can Component A access state from Component B?
  useState

## README

1. What are your learning goals after reading and reviewing the class README?
  I would like to learn the differences between functional components and class components as well as get an understanding of hooks and try to use them in my own code. I want to style more as well.
  