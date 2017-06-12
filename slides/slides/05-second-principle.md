### II

##### The state tree is read only - to change it you must dispatch an action

- an action: the minimal representation of a change to the state
- all mutations to the state are **explicit**, so you can keep track of them (debugging :))
- separation of concerns - components don't need to know how the state works/is structured, they just dispatch an action
- implementation detail: a requirement that every action's type property is not undefined
