# Class 29 Reading Notes

## Extracting State Logic into a Reducer

1. What is the motivation for adding a reducer?
  Reducers allow you to keep your state outside of the component and in one single function. This will keep your logic in one place.

2. What are actions in the context of a reducer? How are they different than setting state directly?
  Reducers are different from setting state because you will dispatch actions to specify what the user just did instead of telling react what you want it to do when you normally set state. Reducers are "more descriptive of the user's intent".

3. What common list operation is useReduce named for, and why?
  

4. When should you switch from useState to useReducer?