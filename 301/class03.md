# Reading
[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)
1) What does .map() return? 

it returns a new element array from a previous array

2) If I want to loop through an array and display each value in JSX, how do I do that in React?

return an element for each item  and store them in a list

3) Each list item needs a unique _identifier___.

4) What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed. 
Keys should be given to the elements inside the array to give the elements a stable identity.


[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab) 

1) What is the spread operator? 

Is the use of an ellipsis of three dots(...) to expand an iterable object into the list of argument

2) List 4 things that the spread operator can do.
* Copying an array
* Using Math functions
* Using an array as argument
* Combining object

3) Give an example of using the spread operator to combine two arrays.
 

const hello = {hello}
const world = {world}

const helloWorld = {...hello,...world}
console.log(helloWorld)  

4) Give an example of using the spread operator to add a new item to an array.
const Arr =['hi', 'bye']
const myItem = {hello}// 
 

const newArr = ['hi', ...myItem,'bye']
console.log(newArr)  
5) Give an example of using the spread operator to combine two objects into one.
const parts = ['shoulders', 'knees'];
const lyrics = ['head', ...parts, 'and', 'toes'];


# Videos
[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)


1)  In the video, what is the first step that the developer does to pass functions between components?

we have a state in an upper component, and the lower component will be triggered

2) In your own words, what does the increment function do?

we use increment to change the state, receiving the name and loop through it , and them modifying the array

3) How can you pass a method from a parent component into a child component?

Passing method as a prop using the arrow function

4) How does the child component invoke a method that was passed to it from a parent component?