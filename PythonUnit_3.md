
peethon nut3
Object-Oriented Programming Object-oriented programming (or OOP for short) is a programming model that organizes the design of code by bundling objects.

Class Instantiation The process of creating an instance of a class which is called an object.

Attributes Attributes are data defined in the class template and are the characteristics or properties of an object. 
class The class keyword defines the data and code that will make up each of the objects. When defining a class, it starts with the class keyword and is then followed by the name of the class and a colon.
. The (.) (dot) operator connects the object (instance of a class) to the attributes and methods of that object

__init__ The __init__ method’s sole purpose is to initialize (assign values) to the object’s attributes and it is only used within a class.

delAAA The del keyword is used to delete objects, and since everything in Python is an object, we can use this keyword to delete anything, including variables, lists, etc.


Inheritance Inheritance is a relationship model that allows us to define a class that inherits all the attributes and methods from another class.
Base Class The base class is also known as the parent class. It is the class that is being inherited from.
Subclass The subclass is also known as the child class. It is the class that inherits from another class. A subclass is known to “extend” the base class, meaning that it can define additional data that will not affect the base class.

super() The super() function allows a subclass to access the base class attributes and methods


Name Collisions Name collisions occur when similar named objects are used in multiple scopes that mean different things. i.e mentioning "dog" in your household refers to your own dog, in a dog park, it refers to any dog.

__main__ The main function is the name of the top-level program in Python. The top level is the first user specified module that runs when a program is being executed.

global The reserved keyword global allows the modification of a variable outside of the current scope.

help() Python has a built-in help() function that you can use with any class to get more information about that class.
Method Resolution Order If a class has a method that exists in multiple classes, the method resolution order tells us which classes will be looked at first

__dict__ The dict method contains a dictionary collection of all of the attributes and methods for that object.


Python Library The Python Standard Library is composed of collections of built-in modules that provide access to system functionality and standardized solutions that Python programmers can utilize when developing programs. 
Packages Packages are a collection of one or more modules that are typically related in functionality.

import The import reserved keyword is used to import modules.
dir() The dir() (directory) function returns the content of the object including all properties and methods without the values.
from The from reserved keyword is used to import only a specified method or property from a module.

random() The random() function returns a float value greater than or equal to 0.0 and less than 1.0. 
randint() The randint() function returns a random integer that’s equal to or between the two values that are supplied as arguments. 
randrange() The randrange() function returns a random integer value within the range of integers that’s specified.

main.py The main.py is the top-level file for all Python programs. Anytime you create a new Python program, main.py will automatically be created for you to use.
Docstring A Python docstring (short for documentation string) is a string used to document a Python module, class, function, or method. This makes it easy for someone to understand what that object does.

Central Processing Unit The Central Processing Unit is the heart of any computer. It is what runs the software that we write; it is also called the “CPU” or the “processor”.
Main Memory The Main Memory is used to store information that the CPU needs in a hurry. Main memory is nearly as fast as the CPU. The CPU and memory are where our software works and runs.
Secondary Memory Secondary Memory is also used to store information, but it is much slower than the Main Memory. The advantage of the Secondary Memory is that it can store information even when there is no power to the computer.
open()
The open() function returns a file object. The open() function contains options for reading the content of the file.

File Handle The file handle is not the actual data contained in the file, but instead, it is a “handle” that we can use to read the data.
.read() The .read() method reads the entire file and returns the entire contents as a string.

.write() The .write() method of the file handle object writes a specified text to the file, returning the number of characters written.

.close() The .close() method of the file handle object closes an open file.

.readlines() The .readlines() method reads the entire file and returns the results as a list.

.readline() The .readline() method reads one line up to a newline character and returns a string.

.replace() The .replace() method replaces a specific phrase in the string with another specified phrase.

exit() The exit() function is a built-in function that we can call that will quit and leave the program. 
sys.exit() The sys.exit() function, which is part of the sys module, allows the termination of a program and can optionally take in an argument such as a number. 
repr() The repr() function takes any object as an argument and returns a string representation of the object. Whitespace Whitespace are characters such as tabs, spaces, and newlines.

Whitespace
Whitespace are characters such as tabs, spaces, and newlines.

with The with statement (a reserved keyword) is used with the open() function and simplifies exception handling as it incorporates all of the common file tasks automatically This includes errors in finding the files, the process of closing the file, and other common issues.

csv.reader() The csv.reader() function, which is part of the csv module, takes a line from the file and splits the data into individual data elements if the data is separated by a comma. 
csv.writer() The csv.writer(), which is part of the csv module, outputs data and automatically adds in commas and quotes to separate out those data elements into .csv file format. 
writerows() The writerows() function, part of the csv module, takes the input from the data lists and adds in the commas and quotes one line at a time. 
enumerate() The enumerate() function returns back the current count of the current iteration to use if we need it and the value of the item at the current iteration.


