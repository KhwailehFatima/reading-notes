# Redux advanced

 **Redux** is an open-source JavaScript library for managing application state. It is most commonly used with libraries such as React or Angular for building user interfaces.

### **What is createSlice in Redux Toolkit?**
createSlice is a higher order function that accepts an initial state, an object full of reducer functions and a slice name. It automatically generates action creators and action types that correspond to the reducers and state.


### To use redux to build an application, follow these steps:

Step 1: Implement createSilce method and export actions and reducer.

* First, import the createSlice method from the redux-toolkit library.
* Make use of createSlice method to create your slice.
* The Slice created above contains all the values required to create a reducer. Now we need to export the actions and the reducer.


Step 2: Dispatch action by making use of react hooks in functional component.

* Now we need to make use of the react hooks useSelector to read the state and useDispatch to dispatch the action created in slice. Let’s implement and see how the app works.


Step 3: Configure the store

* Now we need to connect our store to the app. Here configureStore({}) wraps createStore() to simplify the configuration for us. createStore() is a redux store that holds the complete state tree of your app.