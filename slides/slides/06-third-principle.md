### III

##### State mutations are performed by pure functions, called reducers


- the functions that change the state (reducers) must be pure - they take the current state and the action being dispatched, and return the next state (a new object)
- the next state is therefore a pure function of current state and the dispatched action
- why? enables time-travel debugging
