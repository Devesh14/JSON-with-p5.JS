In this assignment, p5.js is used along with its libraries.
http server is used for local hosting(http-server).
sketch.js contains the original javaScript code.
JSON file is is included in JS file and JSON data is contained in a function called getPokemon.

1. 
step 1: In first function we are getting the information of the pokemon by just entering the name of the pokemon.
		Name is passed via argument, then a loop is run through all the json data.
step 2: An if condition is checked for the name entered by the user, whether the name is true or false.
step 3: If name is is true then information is shown in alert.

2.
step 1: same as function 1. Also an empty array is used(evolutionArray) to store the fetched data.
step 2:'hasOwnProperty' is checked for JSON data because every pokemon data does not contain next_evolution field.
step 3: Now we loop through the next_evolution array.
step 4: Equality of name is checked in if statement.
step 5: Then the fetched data is pushed into the evolutionArray.
step 6: Now a condition is checked whether the evolutionArray is empty or not.
step 7: Then the results are shown as per users demand.  

3.
step 1 and step 2 are same except the weakness property is checked by 'hasOwnProperty'.
step 3: fetched items are pushed in array.
step 4: if weakness is found in weakness array, then print.
step 5: Now a while condition is applied for null or empty on pokemonWeakness which is initialized to null.
step 6: Now the end user can get the output along with the number of pokemons.

Starting p5
step 1: npm install p5-manager -g
step 2: p5 generate -b projectName
You can start to code now.

To make an http-server
npm install -g http-server

To launch server
In console: http-server

