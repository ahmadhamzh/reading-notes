# Passing Functions as Props

### What does .map() return?
  * we use the map() function to take an array of numbers and loop through it and then return a new array with the new data that we procces .

### If I want to loop through an array and display each value in JSX, how do I do that in React?

  * you can build collections of elements with the function map()  and include them in JSX using curly braces {}.

### Keys 
  * Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.
  
  * Each list item needs a unique Key.
  * Keys only make sense in the context of the surrounding array.
  * Keys used within arrays should be unique among their siblings. However, they donβt need to be globally unique. We can use the same keys when we produce two different arrays.
----------------------
### What is the spread operator ?

  * In JavaScript, spread syntax refers to the use of an ellipsis of three dots (β¦) to expand an iterable object into the list of arguments.

###  things that the spread operator can do 
  * Copying an array
  * Concatenating or combining arrays
  * Using Math functions
  * Using an array as arguments
  * Adding an item to a list
  * Adding to state in React
  * Combining objects
  * Converting NodeList to an array

  ### Spreads Examples

         const fruits = ['π','π','π','π','π']
         const moreFruits = [...fruits];
         console.log(moreFruits) // Array(5) [ "π", "π",          "π", "π", "π" ]
         fruits[0] = 'π'
         console.log(...[...fruits,'...',...moreFruits]) //  π          π π π π ... π π π π π
 ----------------   


        const myArray = [`π€ͺ`,`π»`,`π`]
        const ourArray = [...myArray,...yourArray]
        console.log(...ourArray) // π€ͺ π» π π π€ π€©
        const yourArray = [`π`,`π€`,`π€©`]

---------------

         