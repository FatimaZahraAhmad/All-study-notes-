# Python Programming Unit 1

## Programming Fundamentals

### Core Concepts

**Input** - Ways a program gets its data; user input through the keyboard, mouse, or other device.

**Processing** - Takes the data inputs and prompts and calculates the results (output).

**Output** - The results at the end of a program based on user input and system processing.

**Algorithm** - A logical step-by-step plan that we need to build for solving a problem.

**Pseudo-code** - English-like statements that describe the steps in a program or algorithm.

### Language Processing

**Syntax** - The "grammar" rules of the programming language. Each programming language (like Python) has its own syntax.

**Compiler** - Scans an entire program and attempts to convert the whole program at once to machine code.

**Interpreter** - Takes the bytecode one line at a time and converts it to machine code.

**Machine Code** - Also known as machine language. The computer uses binary (0s and 1s) to perform tasks.

**Bytecode** - An intermediary step for code conversion between the programming language that you write and the machine code that a computer uses.

**Virtual Machine** - A software program that behaves like a completely separate computer within an application.

## Development Environment

### Tools and Components

**Integrated Development Environment (IDE)** - A text editor that has additional functionality to allow developers to perform additional tasks to simplify the workflow of the development process.

**Libraries/Library** - Pre-written code collections that you can use when developing a program.

**Module** - A self-contained piece of code that can be used in different programs.

**Comments** - The "#" (hashtag) is used in Python code to identify a comment. Commented lines of code are ignored by the compiler during runtime.

## Variables and Data Types

### Variable Concepts

**Variable** - A named memory location that has the ability to hold various distinct values at different points in time in the program.

**Value** - One of the basic units of data, like a number or string, that a program manipulates.

**= (Assignment Operator)** - The = operator (equal sign) is an assignment operator that is used to assign values to variables.

**Statement** - A unit of code that the Python interpreter can execute.

**Expression** - A combination of values, variables, and operators.

### Naming Conventions

**Camel Case** - Combining words where each word except the first word will start with a capital letter.

**Pascal Case** - Combining words where each word starts with a capital letter.

**Snake Case** - Combining words where each word is separated by an underscore and all of the words are in lowercase.

### Data Types

**String (str)** - A text data type consisting of characters that are enclosed in either single or double quotes.

**Integer (int)** - A numeric data type consisting of an integer or a whole number. It can be positive or negative but does not have decimals.

**Float** - A numeric data type referring to a floating-point number. It can be positive or negative and uses decimal values.

**Complex** - A numeric data type consisting of a number that is the sum of a real number and an imaginary number.

**Boolean (bool)** - A boolean data type consisting of a value of either True or False.

### Type Functions

**type()** - The type() function takes a value or variable as input and returns the type of the value or variable.

**Casting (or Type-Casting)** - Converting a variable's value from one data type to another.

## String Operations

### String Properties

**Literal String** - A series of characters that are combined together and enclosed in quotes.

**Empty String** - A string that is identified but does not contain anything; it is essentially empty.

**Concatenation** - The operation of joining or merging two or more strings together.

### Escape Characters

**Escape Character** - Special characters that when added to a string will allow quotes of a string to be escaped.

Examples:
- `\` - Placing the \ at the end of a line, the backslash and newline are ignored.
- `\\` - Outputs the backslash.
- `\'` - Outputs the single quote.
- `\"` - Outputs the double quote.
- `\b` - The \b stands for backspace and removes the character prior to the \b.
- `\n` - The \n adds a new line after each \n.
- `\t` - The \t adds a tab.

### String Methods

**capitalize()** - Converts the first character of the string to uppercase with all other characters to lowercase.

**index()** - Can find the location of a character or a string within another string.

**lower()** - Converts all characters of a string to lowercase including the first character.

**swapcase()** - Returns a copy of the string with uppercase characters converted to lowercase and lowercase characters converted to uppercase.

**title()** - Returns a copy where the first letter of each word is converted to uppercase with other characters converted to lowercase.

**upper()** - Converts all characters of a string to uppercase.

## Operators

### Arithmetic Operators

**+ (Addition)** - The + operator adds integers or concatenates strings (joins them end to end). Mixing strings and integers with + causes an error.

**\* (Multiplication)** - The * operator multiplies integers or replicates strings (repeats them) based on an integer multiplier. It doesn't work with floats for replication.

**in (Membership)** - The in operator checks if a value is in a sequence (returns True or False) and can also loop through sequences in a for loop.

## Functions

### Function Concepts

**Functions** - A section of code that runs when it is called. We can pass data into functions, which are called parameters.

**Argument** - An actual value(s) that is being passed into the function when it is being called.

**print()** - The print() function allows Python to send data to the output screen.

## Control Flow

### Conditional Statements

**Conditional Statement** - A statement that controls the flow of execution depending on some condition.

**Condition** - A boolean expression in a conditional statement that determines which branch is executed.

**Compound Statement** - A statement that consists of a header line that ends with the colon character (:) followed by an indented block. It stretches across more than one line.

**pass** - A pass statement is a reserved keyword that is essentially a statement that will do nothing.

### Boolean Operators

**and** - The and operator is a reserved keyword and boolean operator that takes two arguments and returns False unless both inputs are True.

**or** - The or operator is a reserved keyword and boolean operator that outputs True if either input is True (or both).

**Short-Circuit Evaluation** - When the evaluation of a logical expression stops because the overall value is already known.

**Truth Table** - A small table that lists every possible input value and gives results for the operators.

**Boolean Operators** - Also known as logical operators, allow us to build and combine more complex boolean expressions from more basic expressions.

## Error Handling

### Exception Concepts

**Traceback** - A list of functions that are executed and printed to the screen when an exception occurs.

**Exceptions** - Errors detected during execution (running of the code) are called exceptions.

**try and except** - Reserved keywords where you know that some sequence of instructions may have a problem and you want to add statements to be executed if an error occurs. The except block is ignored if there is no error.

**as** - A keyword used to create an alias.

## Testing

### Testing Concepts

**Syntax Error** - A syntax error means that you have violated the "grammar" rules of Python.

**Edge Case** - Values that are at the end of a testing range.

**Interior Test** - Test values that are within a specific range where the precise values entered within that range did not matter.

**Corner Case** - The value you are testing is in between two edge cases.