1. What problem does the context API help solve?
  - Context API enables us to share specific forms of data across all levels of the application.

1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? 
Why is the store known as a 'single source of truth' in a redux application?
  - Actions (information), Reducers (functions), and the Store (holds state) make easier to manage state and data. The single source of truth helps to create universal apps. It only allows the state to be stored in one location being the store. 

1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
  - Application state is global while Component state is local. Application can be accessed anywhere from the app but compenent state can only be changed within a component.

1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
  - Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object.

1. What is your favorite state management system you've learned and this sprint? Please explain why!
  - I like redux because it seems very useful when building complex applications. It also makes things easier and more predictable by making state immutable. 
