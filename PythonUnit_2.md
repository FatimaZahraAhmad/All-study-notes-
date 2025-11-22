​

Data Collection Type A data collection type is a collection of related values that are organized in a specific way so that they can be used effectively.
List The list is the simplest data collection type in Python and it can store multiple values in a single variable.

Element An element is one of the values in a list (or other data collection type); elements can also be called items.
Index The index (also known as position) is an integer value that indicates an element in a data collection type like a list.

Mutable Mutable means that we’re able to change items, add items, or delete items from a data collection type after it has been created.

slice The slice operator also works on lists to allow us to return or update specific elements within the list. The slice operator works on any data collection types that are ordered, so this operator will work with lists and tuples.

.append() The .append() method allows us to add a new element to the end of a list or other data collection type.
.insert() The .insert() method allows us to add an element to a list or other data collection type, in any position.
.extend() The .extend() method takes a list (or other data collection type) as an argument and then appends (or adds) all of those elements to the end of another list or data collection.

.sort() The .sort() method arranges all of the elements in a list (or other data collection type) from the lowest to highest. If the values are strings, the result will be a list of strings in alphabetical order.

"
.pop() The .pop() method modifies the list (or other data collection type) and returns the element that was removed.
del del is a reserved keyword and used as the del statement to delete an element. It does not return anything.
.remove() Use the .remove() method if we know the element of a list (or other data collection type) we wish to remove (but not the index); the .remove() method takes away the first instance that the element occurs. If the element does not exist, using this method will raise an error.

max() The max function (stands for maximum) returns the largest value in a list (or other data collection type).

min() The min function (stands for minimum) returns the smallest value in a list (or other data collection type).

len() The len function (stands for length) returns the number of elements in a list (or other data collection type).

sum() The sum function returns a number, sum of all values in a list (or other data collection type).

Iteration Iteration is the repetition of a process. For programming, that is basically the repetitive execution of code to do something.
Iterable Iterable sounds complex but it is just a fancy name for a Python object that is capable of going through its members one at a time.
Iterator Iterator is a type of object that contains a countable number of values. More simply, the iterator is an object that can be used to traverse and move through all its values (elements) within an iterable object.
iter() The iter() function is used to create an iterator by initializing the object that was passed to it.
next() The next() function is used to move to the next value (element) in an iterable object.

add() Once a set is created, if we wanted to add an element to a set, we would use the .add() method. If the element already exists, the .add() method will not add the element to the set.
.update() Use the .update() method to add elements from another iterable object (data collection type) into the current iterable object. If an element exists in both objects, only one element will be updated to the combined data collection type.
.discard() The .discard() method removes a specified element from the data collection type object. The .discard() method will not raise an error if the element does not exist in the object.

Sets Sets are a data collection type that is used to store multiple elements in a single variable similar to the other data collection types. Set elements are unordered and we cannot change the elements in the set after the set has been created. However, we can add new elements to the set

Tuple A tuple is a data collection type that is ordered and unchangeable. This means that a tuple uses an indexing structure for its order and its elements can’t be changed after it has been defined.

dict() The dict() function creates a new dictionary with no elements.

2D (Two Dimensions) A nested list or other data collection type (iterable objects like lists, set, tuple, or dictionary) inside another iterable object is called two-dimension or 2D for short. Any data collection type can contain other nested collection types as well in multiple dimensions.



/////////////////////////////////
// Operators //
/////////////////////////////////
Operators are specific units, or interactive things, like adding, subtracting (- , + operators), assigning a valuable (= , += operators), and etc, they go in boolean operators, meaning true or false output.


/////////////////////////////////
// In operator //
/////////////////////////////////

we can check the contents of a lists (not just lists!) to see if it has a element or not, it is like the include function in javascript.

/////////////////////////////////
// = operator //
/////////////////////////////////


the = operator makes some element a specific thing, like if you want to change 3 to 4, you can do this: " arrayouwantochange[x] = [4]
"


/////////////////////////////////
// + operator //
////////////////////////////////


the + operator concatenates any element, and it can add numbers, floats, and others aswell.



/////////////////////////////////
// * operator //
////////////////////////////////

the * operator multiplies something with another number, and it can duplicate that thing aswell.


move hand

/////////////////////////////////
// slice operator //
////////////////////////////////

the slice operator allows us to return or update specific elements, the slice operator works on any data collection types we order, and it can return specific elements and those elements only.

2. Methods and Functions

2A. .append() Method

the .append() method allows us to add a new element to the end of a list or other data collection type.


2B. .insert() Method
there are times when we want to place something in a SPECIFIC order in the list, we can use the insert method for that! just add the element number, and it'll go right there.

2C. .extend() Method
The .extend() method takes a list (or any other data collection type) as an argument and appends (adds) all of those elements to the end of another list or data collection.

2D. .sort() Method
the .sort() Method arranges all the elements int he data collection type from the lowest to the highest, if the elements are strings, the result will be in alphabetical order.

2E. .pop() Method
the .pop() method removes a specific element from the data collection type, and returns the element that was removed, without an index included, it deletes the last element.

2F. .del Statement
we can use the del statement (delete) if we don't need to worry about the element that was removed. the del statement deletes an element but doesn't return anything.

2G. .remove Method
we can use the .remove() method if we know the element we want to remove, but not the index, the remove method takes away the first instance that the element occurs, and if it doesn't exist, it will raise an error.



3. Iterables and Iterators
The next two functions we are going to discuss are the iter() and next(). First, we need to explain what iterators and iterables are. Lists and the other data collection types (sets, tuples, and dictionaries, which we will go into in more detail in the next lesson) are iterable types and can make use of 
iterators. 

The function, which is used to create an iterator by initializing the object that was passed to it.

The next() function, which is used to move to the next value (element) in an iterable object.

Tuples
tuples are also a data collection type, they aren't mutable (meaning changeable), not even adding something to them, they come in round brackets.


Dictionary A dictionary is like a list, but more generalized. Dictionaries store data values in key:value pairs that are changeable, meaning that we can change, add or remove elements after the dictionary has been created. Dictionaries cannot have two elements of the same key.

key:value pair Used with the dictionary data collection type. Think of a dictionary as a mapping between the index positions (which are called the keys) and a set of values (elements). Each key maps to a value. The association of a key and a value (element) is called a key:value pair.

dict() The dict() function creates a new dictionary with no elements.

.values() The .values() method returns an object that contains the values of the dictionary as a list.

2D (Two Dimensions) A nested list or other data collection type (iterable objects like lists, set, tuple, or dictionary) inside another iterable object is called two-dimension or 2D for short. Any data collection type can contain other nested collection types as well in multiple dimensions.

None The type None is a return type that simply means that there is no data that’s returned.
strip() The .strip() method is a string method that removes any spaces before the first character or after the last character.

Indefinite Iteration A loop that is not specified in advance on how many times to be run; it repeats as long as a condition is met. In Python, indefinite loops are typically created using the while loop.
Definite Iteration With definite iteration, the number of times the block of code runs should be explicitly defined when the loop actually starts. Typically, this is implemented using the for loop. The for loop has a specific start and endpoint.

Iteration Variable The body of the loop should change the value of one or more variables so that eventually the condition becomes false and the loop terminates. The variable that changes each time the loop executes and controls when the loop finishes is called the iteration variable. If there is no iteration variable, the loop will repeat forever, resulting in an infinite loop.

while The while loop is one of the most commonly used loops. It keeps going as long as some condition is true.

did dad put the 1 hr timer on..???

Body of the Loop The body of the loop represents the indented block of code that should be executed repeatedly within the loop during each loop iteration.
Iteration Variable The variable that changes each time the loop executes and controls when the loop finishes.

Infinite Loop An infinite loop is a loop in which the terminating condition is never satisfied or for which there is no terminating condition.

for In Python, definite iteration loops are generally called for loops. Python’s for loop is a data collection-based iteration (loops through iterable objects such lists, sets, tuples, dictionaries, and even strings).
range() The range() function takes multiple parameters, the starting number (0 by default), and the ending number. This function will increment by 1 (by default) and then stop before a designated number. The function can take an optional third parameter to change the step value (increment or decrement by a specific value other than the default of 1).



break This is a reserved keyword that creates a break statement for loops. The break statement can immediately terminate a loop’s execution. When this occurs, the program goes to the first statement/line of code after the loop.
continue This is a reserved keyword that creates a continue statement for loops. The continue statement will end the current loop iteration, meaning that the execution jumps back to the top of the loop. The expression is then evaluated to determine if the loop will execute again or end there.



end The end parameter is a function of the print() function. Using the end parameter, we are able to change the default operation of the print() function, namely to prevent the print() function from creating a new line.

Debugging by Bisection Debugging by bisection is the practice of breaking your program code into “sections” for debugging and validation purposes. This will help speed up the debugging process since you may be able to find issues within a section rather than the full program.

Function Definition A function definition specifies the name of a new function and the sequence of statements that execute when the function is called.
def The reserved keyword def indicates that you are defining a function


Return Statement The return statement is an important part of functions and methods as it allows the functions and methods to return Python objects back to the code that called them. The return statement is the actual line that starts with the word "return".
Return Value These objects that are being returned from the return statement are called the function or method’s return value

Return
The reserved keyword return is used to exit a function and return a value, either an optional return value we specify or none if no value is specified.

divmod() The divmod() function takes in two numbers as arguments and returns two numbers in a tuple.


Flow of Execution The order in which statements are executed is called the flow of execution. Execution always begins at the first statement of the program. Statements are executed one at a time, in order from top to bottom.

Local Scope Local scope means that the variables can only be accessed within the block, function, method, or class that they are initialized or used.
Global Scope Global scope means variables can be accessed throughout the entire program


