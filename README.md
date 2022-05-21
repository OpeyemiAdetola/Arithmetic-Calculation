# module-3-assignment

## Assignment: arithmetic calculation
February 2022
- complete arithmetic assignment
index.html file used for user input of values and operation
index.js file uses imported module and inputs from index.html form to calculate math operations

## assignment prompt:
Create a new folder for the project and name it “Arithmetic Calculation”.
Initialize NPM to create package.json file and install Express library.
Create an index.js file and set up a server inside of it.
Create a POST route, which will receive three post data: operation, value_1, and value_2. The operation post data can only have any of these four (4) values: add, sub, mul, and div. The value_1 and value_2 post data refers to two numbers. Based on the operation specified, an arithmetic computation will be performed on the two numbers.
Create a custom module called arithmeticFunctions.js. Export the following functions from it:
add(value_1, value_2): This will return the addition of the two numbers passed as a parameter.
sub(value_1, value_2): This will return the subtraction of the two numbers passed as parameters.
multiply(value_1, value_2): This will return the multiplication of the two numbers passed as a parameter.
divide(value_1, value_2): This will return the division of the two numbers passed as a parameter.
Import the custom module into index.js.
Based on the value of the operation, call the appropriate function from the custom module and pass value_1 and value_2 into the function.
Print result to console using the following format:
Operation: Addition.

Thank you,
Opeyemi


