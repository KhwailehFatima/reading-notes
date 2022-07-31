 # Reading 

 [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

 1) What is the single responsibility principle and how does it apply to components?

 every class, module, or function in a program should have one responsibility/purpose in a program. Should do one thing

2) What does it mean to build a ‘static’ version of your application?

is to build components that reuse other components and pass data using props

3) Once you have a static application, what do you need to add?
requires alot of typing and no thinking , and adding interactivity requires a lot of thinking and not a lot of typing


4) What are the three questions you can ask to determine if something is state?
 Ask three questions about each piece of data:

* Is it passed in from a parent via props? If so, it probably isn’t state.
* Does it remain unchanged over time? If so, it probably isn’t state.
* Can you compute it based on any other state or props in your component? If so, it isn’t state.


5) How can you identify where state needs to live?

state lives in FilterableProductTable.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1) What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them

2) Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
it takes the value which is greater than 10



3) Explain how either map or reduce operates, with regards to higher-order functions.

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values.