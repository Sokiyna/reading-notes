## Lists and Keys
1. An array containing the results. 

2- 

const elements = [] //..some array

const items = []

for (const [index, value] of elements.entries()) {
  items.push(<Element key={index} />)
}


3- Key 

4-  is an inset on a map that explains the symbols, provides a scale, and usually identifies the type of map projection used.

## Spread Operator
1- The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a functionβs arguments.

2- 

Copying an array
Concatenating or combining arrays
Using Math functions
Using an array as arguments
3- concat method.

4- 

const fewFruit = ['π','π','π']
const fewMoreFruit = ['π', 'π', ...fewFruit]
console.log(fewMoreFruit) // Array(5) [ "π", "π", "π", "π", "π" ]
 5- 

const objectOne = {hello: "π€ͺ"}
const objectTwo = {world: "π»"}
const objectThree = {...objectOne, ...objectTwo, laugh: "π"}
console.log(objectThree) // Object { hello: "π€ͺ", world: "π»", laugh: "π" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("π".repeat(5))}}
objectFour.laugh() // πππππ
 1- The developer made a function. 

2- he made it to pass the person object, to know which person he he is changing and what the increment. 

3- By having a reference.

4- change the state and rerender.