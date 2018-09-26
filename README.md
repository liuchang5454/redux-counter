# redux-counter

App Description:
- a minimal app using Redux
- the count is displayed 
- click INCREMENT / DECREMENT button to call state.dispatch() to update state

Flow:
0 - create a reducer with some inital state
1 - create a store -> the reducer is run and our inital state is defined
2 - whenever we want to see our state -> state.getState()
3 - whenever we want to make a change to our state -> store.dispatch(action)
    4 - note actions are objects
    5 - note actions must have a key of "type"
6 - writing a function that returns an object
    7 - write a function that returns an action
