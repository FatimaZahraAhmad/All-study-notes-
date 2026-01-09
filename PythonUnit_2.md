# Python Programming Unit 2

## Data Collection Types

### Basic Concepts

**Data Collection Type** - A collection of related values that are organized in a specific way so that they can be used effectively.

**Element** - One of the values in a list (or other data collection type); elements can also be called items.

**Index** - The index (also known as position) is an integer value that indicates an element in a data collection type like a list.

**Mutable** - Mutable means that we're able to change items, add items, or delete items from a data collection type after it has been created.

### Lists

**List** - The simplest data collection type in Python and it can store multiple values in a single variable.

#### List Methods

**.append()** - Allows us to add a new element to the end of a list or other data collection type.

**.insert()** - Allows us to add an element to a list or other data collection type, in any position.

**.extend()** - Takes a list (or other data collection type) as an argument and then appends (or adds) all of those elements to the end of another list or data collection.

**.sort()** - Arranges all of the elements in a list (or other data collection type) from the lowest to highest. If the values are strings, the result will be a list of strings in alphabetical order.

**.pop()** - Modifies the list (or other data collection type) and returns the element that was removed. Without an index included, it deletes the last element.

**del** - A reserved keyword and used as the del statement to delete an element. It does not return anything.

**.remove()** - Use if we know the element of a list we wish to remove (but not the index); takes away the first instance that the element occurs. If the element does not exist, using this method will raise an error.

#### List Functions

**max()** - The max function (stands for maximum) returns the largest value in a list (or other data collection type).

**min()** - The min function (stands for minimum) returns the smallest value in a list (or other data collection type).

**len()** - The len function (stands for length) returns the number of elements in a list (or other data collection type).

**sum()** - Returns a number, sum of all values in a list (or other data collection type).

### Tuples

**Tuple** - A data collection type that is ordered and unchangeable. This means that a tuple uses an indexing structure for its order and its elements can't be changed after it has been defined. Tuples come in round brackets.

### Sets

**Sets** - A data collection type that is used to store multiple elements in a single variable similar to the other data collection types. Set elements are unordered and we cannot change the elements in the set after the set has been created. However, we can add new elements to the set.

#### Set Methods

**.add()** - Once a set is created, if we wanted to add an element to a set, we would use the .add() method. If the element already exists, the .add() method will not add the element to the set.

**.update()** - Use the .update() method to add elements from another iterable object (data collection type) into the current iterable object. If an element exists in both objects, only one element will be updated to the combined data collection type.

**.discard()** - Removes a specified element from the data collection type object. The .discard() method will not raise an error if the element does not exist in the object.

### Dictionaries

**Dictionary** - Like a list, but more generalized. Dictionaries store data values in key:value pairs that are changeable, meaning that we can change, add or remove elements after the dictionary has been created. Dictionaries cannot have two elements of the same key.

**key:value pair** - Used with the dictionary data collection type. Think of a dictionary as a mapping between the index positions (which are called the keys) and a set of values (elements). Each key maps to a value.

#### Dictionary Functions and Methods

**dict()** - Creates a new dictionary with no elements.

**.values()** - Returns an object that contains the values of the dictionary as a list.

### Multi-dimensional Data

**2D (Two Dimensions)** - A nested list or other data collection type (iterable objects like lists, set, tuple, or dictionary) inside another iterable object is called two-dimension or 2D for short. Any data collection type can contain other nested collection types as well in multiple dimensions.

## Iteration and Iterators

### Iteration Concepts

**Iteration** - The repetition of a process. For programming, that is basically the repetitive execution of code to do something.

**Iterable** - Iterable sounds complex but it is just a fancy name for a Python object that is capable of going through its members one at a time.

**Iterator** - A type of object that contains a countable number of values. More simply, the iterator is an object that can be used to traverse and move through all its values (elements) within an iterable object.

### Iterator Functions

**iter()** - Used to create an iterator by initializing the object that was passed to it.

**next()** - Used to move to the next value (element) in an iterable object.

## Operators

### Basic Operators

**Operators** - Specific units, or interactive things, like adding, subtracting (-, + operators), assigning a value (=, += operators), and etc, they go in boolean operators, meaning true or false output.

#### In Operator
**in** - We can check the contents of lists (not just lists!) to see if it has an element or not, it is like the include function in JavaScript.

#### Assignment Operator
**=** - Makes some element a specific thing, like if you want to change 3 to 4, you can do this: "array_you_want_to_change[x] = 4"

#### Concatenation Operator
**+** - Concatenates any element, and it can add numbers, floats, and others as well.

#### Multiplication Operator
**\*** - Multiplies something with another number, and it can duplicate that thing as well.

#### Slice Operator
**slice** - Allows us to return or update specific elements, the slice operator works on any data collection types we order, and it can return specific elements and those elements only.

## Loops and Control Structures

### Loop Types

**Indefinite Iteration** - A loop that is not specified in advance on how many times to be run; it repeats as long as a condition is met. In Python, indefinite loops are typically created using the while loop.

**Definite Iteration** - With definite iteration, the number of times the block of code runs should be explicitly defined when the loop actually starts. Typically, this is implemented using the for loop. The for loop has a specific start and endpoint.

### Loop Components

**Body of the Loop** - The indented block of code that should be executed repeatedly within the loop during each loop iteration.

**Iteration Variable** - The variable that changes each time the loop executes and controls when the loop finishes. The body of the loop should change the value of one or more variables so that eventually the condition becomes false and the loop terminates.

**Infinite Loop** - A loop in which the terminating condition is never satisfied or for which there is no terminating condition. If there is no iteration variable, the loop will repeat forever.

### Loop Statements

**while** - The while loop is one of the most commonly used loops. It keeps going as long as some condition is true.

**for** - In Python, definite iteration loops are generally called for loops. Python's for loop is a data collection-based iteration (loops through iterable objects such lists, sets, tuples, dictionaries, and even strings).

**range()** - Takes multiple parameters, the starting number (0 by default), and the ending number. This function will increment by 1 (by default) and then stop before a designated number. The function can take an optional third parameter to change the step value (increment or decrement by a specific value other than the default of 1).

### Loop Control

**break** - A reserved keyword that creates a break statement for loops. The break statement can immediately terminate a loop's execution. When this occurs, the program goes to the first statement/line of code after the loop.

**continue** - A reserved keyword that creates a continue statement for loops. The continue statement will end the current loop iteration, meaning that the execution jumps back to the top of the loop. The expression is then evaluated to determine if the loop will execute again or end there.

## Functions

### Function Definition

**Function Definition** - Specifies the name of a new function and the sequence of statements that execute when the function is called.

**def** - The reserved keyword that indicates you are defining a function.

### Return Values

**Return Statement** - An important part of functions and methods as it allows the functions and methods to return Python objects back to the code that called them. The return statement is the actual line that starts with the word "return".

**Return Value** - The objects that are being returned from the return statement are called the function or method's return value.

**return** - The reserved keyword used to exit a function and return a value, either an optional return value we specify or none if no value is specified.

### Special Functions

**divmod()** - Takes in two numbers as arguments and returns two numbers in a tuple.

### Execution Flow

**Flow of Execution** - The order in which statements are executed. Execution always begins at the first statement of the program. Statements are executed one at a time, in order from top to bottom.

### Variable Scope

**Local Scope** - Variables can only be accessed within the block, function, method, or class that they are initialized or used.

**Global Scope** - Variables can be accessed throughout the entire program.

## String Operations

### String Methods

**strip()** - A string method that removes any spaces before the first character or after the last character.

### Print Function

**end parameter** - A function of the print() function. Using the end parameter, we are able to change the default operation of the print() function, namely to prevent the print() function from creating a new line.

## Debugging

### Debugging Techniques

**Debugging by Bisection** - The practice of breaking your program code into "sections" for debugging and validation purposes. This will help speed up the debugging process since you may be able to find issues within a section rather than the full program.

## Special Data Types

### None Type

**None** - The type None is a return type that simply means that there is no data that's returned.