# Class 03 -reading note

## React Docs - lists and keys

### What does .map() return?
Array.map return a new array
### If I want to loop through an array and display each value in JSX, how do I do that in React?
Set a variable to store the array. Ex: let newArr = arr.map()
### Each list item needs a unique Key
What is the purpose of a key? Key help react know which item has been updated, changed, or moved. 

## The Spread Operator
What is the spread operator?  The spread operator allows us to copy all or part of the array or object into another array or object quickly.
### List 4 things that the spread operator can do. 
Copy array, concatenate or combine arrays, use with Math functions, and use it as an argument with the array. 
### Give an example of using the spread operator to combine two arrays. 
    Const arr1 = [1,2,3]		const arr=[2,3,4]		let arr3 = [...arr1, …arr2] 
### Give an example of using the spread operator to add a new item to an array.
     let arr4 = [10, 20, 30 ...arr1] 
### Give an example of using the spread operator to combine two objects into one.
    const object1 ={ } 	const object2 ={} 	const object3 ={...object1, …object2}

## React-How to pass Function btween components
### In the video, what is the first step that the developer does to pass functions between components? 
Set a name and this.functionName in return 
### In your own words, what does the increment function do?
The increment function will add 1 to count every time when the button is clicked. 
### How can you pass a method from a parent component into a child component? 
Use props
### How does the child component invoke a method that was passed to it from a parent component?
Use this.props.functionName


[Lists and Keys](https://reactjs.org/docs/lists-and-keys.html#rendering-multiple-components)

[How to use Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

[video: React - How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
