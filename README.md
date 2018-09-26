# redux-counter

App Description:
- a minimal app using Redux
- the count is displayed 
- click INCREMENT / DECREMENT button to call state.dispatch() to update state

Flow:
- create a reducer with some inital state
- create a store -> the reducer is run and our inital state is defined
- whenever we want to see our state -> state.getState()
- whenever we want to make a change to our state -> store.dispatch(action)
  - note actions are objects
  - note actions must have a key of "type"
- writing a function that returns an object
  - write a function that returns an action
