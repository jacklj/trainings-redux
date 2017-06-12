### Dispatching actions - how does this work?

The dispatch function simply calls the reducer function on the action and current state, and saves whatever value it returns

mapDispatchToProps:
- a function that takes dispatch and returns functions that dispatch actions, i.e. it binds action creators with the dispatch function
- Shorthand - if the desired function takes the same arguments as the action creator, you can use the object shorthand instead of explicitly binding action creators with dispatch, that maps the names of the callback props to the corresponding (bound) action creators
