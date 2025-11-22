
Web dev 3


The standard for JavaScript is made by the ECMA association, the latest standard is ECMAScript 2023(ES14). 

European Computer Manufacturer Association (ECMA) A standards organization for programming languages and technologies.

ECMAScript 2023 (ES14) The latest standard of JavaScript.

Document Object Model (DOM)
A JavaScript interface that represents a web-page's structure and lets you interact with and change its elements dynamically.

JS code can be located in the following areas:
Within <script></script> in the head or body of the HTML page
Within quote marks as a value for an element’s HTML attribute, such as an event listener like onClick
In an external .js file linked to using the <script> tag within the head

Function
A reusable piece of code that does task(s) and can be called to execute those tasks when needed, (Like an event listener for example, seen below.)

Event Listener
A programming object that listens for specific events to come before executing a function.

You can add a comment in your code by two methods, 

1. place a double forward slash "//" at the beginning

2.Place a forward slash and an asterisk "/*" and end it with the opposite, a asterisk and a forward slash "*/".


Variable
A named location in the computer’s memory where data can be stored and retrieved during the execution of a program.
variables are made with the keyword (var, let, const) followed by a name.

var The keyword for declaring a globally accessible, mutable, function-scoped variable in JavaScript. 
let The keyword for declaring a locally accessible, mutable, block-scoped variable in JavaScript. 
const The keyword for declaring a locally accessible, immutable, block-scoped variable in JavaScript.


Scope The boundaries of a section of code, usually indicated with a set of curly brackets. 
Nonhomogeneous Elements of different types. 
Literals Specific syntax within code that defines an actual piece of data or a value.

Event A specific occurrence or user interaction, such as a user’s click, key press, or a system-generated change, that can trigger code execution or responses in a web application. 
Function Call The act of executing a function to perform its defined tasks or operations. 
Arguments In programming, arguments are values passed when functions are called; they are the values provided within the parentheses. 
Parameters The variables defined within the parentheses in the head of a function definition, which will receive the argument data and can be used within the body of the function. 
Function Declaration A traditional approach to defining a function that starts with the function keyword, the identifier of the function, the parameter list, and a block of commands. 
Function Expression A different approach to defining a function that starts with a variable declaration, which is assigned a function definition that begins with the function keyword, the parameter list, and the body of commands.
Arrow Function A different approach to defining a function that does not contain a name or identifier instead is simply defined by including the parentheses, the arrow “=>”, and then a block of code.


the three types of arrow functions:
version 1: array.map( x => x * 2 );

version 2: array.map( ( num1, num2 ) => num1 * num2 );

version 3: array.map( ( num1, num2 ) => { let result = num1 * num2; return result; }

Event A specific occurrence or user interaction that can trigger code execution or responses in a web application.

Function Call The act of executing a function to perform its defined tasks or operations.

Arguments In programming, arguments are values passed when functions are called; they are the values provided within the parentheses. i.e (3, 1)
in the example, the parentheses are the brackets that keep the placeholders num1, and num2.

Parameters The variables defined within the parentheses in the head of a function definition, which will receive the argument data and can be used within the body of the function.

Function Declaration
A traditional approach to defining a function that starts with the function keyword, the identifier of the function, the parameter list, and a block of commands.

Arrow Function A different approach to defining a function that does not contain a name or identifier instead is simply defined by including the parentheses, the arrow “=>”, and then a block of code. 
Callback Function A function that is provided to another function as an argument and then called within the body of the other function.

Declared To create a named location in memory. 
Initialized To assign the first value to a newly defined variable. 
Expression A series of objects, operators, and values that are evaluated by the system, with a final result being returned.

Number A data value that is numeric in nature and can be operated on using mathematical operators. 
Radix Point Punctuation, usually a comma or period, that denotes the change from fractional digits to whole digits. 
Digit Group Separator Punctuation, usually a comma or period, that denotes the change from thousands to millions, billions, and so on.

Concatenate To append together, end to end. 
Index In programming, the value of an element’s location in a collection, beginning with 0 as the first element. 
Index Indicator A special syntax appended to the end of a collection object that includes a set of square brackets and a whole number between to indicate the position of the element being accessed.

Collections Objects that can hold more than one individual value element under a single identifier. 
Arrays A type of collection object where each element is automatically assigned an index value. 
Condition Statement A programming expression that evaluates to a true or false outcome and is used to control the flow of a program’s execution

Control Manipulation of the flow of execution so that an application responds appropriately based on the different inputs provided. 
Decision Structure A set of programming code that evaluates the true/false value of a condition statement and, based on that evaluation, executes one of multiple pathways of commands. 
Iterative Structure Also referred to as a loop; code structure that evaluates a condition statement, and as long as the condition evaluates to true, the block of code will execute repeatedly, rechecking the condition statement after completing one pass through the code block. 
IF/IF-ELSE
A common programming structure that controls the flow of execution depending on the evaluation of a true/false condition statement. 
Logical Operators Operators used to combine the results of multiple condition expressions into a single output, based on the truth table of the logical operator. 
Truth Table A table used to illustrate the outcome of multiple binary inputs for different logical operators.

Interpolate A programming process wherein special syntax is used to weave object data throughout a string of literal text.

Programming Handle
An object or variable that represents another object in memory.



AJAX (Asynchronous JavaScript And XML)
A technique which uses the asynchronous architecture of JavaScript to:

1. issue a "GET" request to the server without forcing the page to reload

2. when the server transmits the data, AJAX senses the response and triggers the handler function.

in summary, this technique is used to make web-pages more dynamic and interactive.

__


Handler Function A function assigned to listen for and handle an event or response.
XMLHttpRequest (XHR) The object used in JavaScript to prepare and transmit an AJAX request.

The different between AJAX and XHR is that AJAX is a technique, XHR is the main function used in it.

_

indicates the received response status code from the server.
Request Headers Parts of an HTTP request that are communicated to the server prior to the rest of the request that provides helpful data and information to the server.

Canvas Element An HTML element that uses JavaScript to draw graphics onto the canvas itself

Path A line that is defined using coordinates and mathematical methods to draw straight lines, arcs, and Bezier curves.

Color Stop A defined color for a color gradient that also specifies the location of the color in the gradient as a value between 0.0 and 1.0. 
Gradient A method of coloring an element on the screen wherein the fill changes from one color to another.

Scripting Language Processing Engine Server-based software that executes language-specific code contained within a script file, replacing the script code with the text-based output that results from the code’s execution.

Internet Information Service (IIS) software ;;.3that hosts files and resources online and responses to HTTP requests. 
ASP.NET Server-side framework designed for web development and server-side scripting used for creating dynamic web-page content. 
Java A common, high-level object-oriented programming language that can be used as a server-side scripting language, as well as platform-independent applications. 
Python A popular, high-level general-purpose programming language that works well as a server-side scripting language.
Ruby on Rails A server-side web application framework designed for rapid development of model-view-controller-based web services, pages, and databases.
Apache A popular, free, open-source HTTP server.
Nginx A free, flexible, open-source HTTP server.

PHP (Hypertext Preprocessor)
a powerful, general-purpose, open-source scripting language.

“heredoc” Statement Special syntax that interprets the text within a code file without processing the code and instead treats it as plain text.

Constant Variables Variables defined in such a manner that their value cannot be changed for the life of the program. 
Class Definition A set of code in object-oriented programming that defines the structure of an object.

Custom-Defined PHP Functions Callable, named sets of code in PHP, written by the developer. 
Recursive Function Calls When a programming function makes a call to itself. 
Default Arguments When defining a function, default arguments create an optional parameter that, if omitted at the time of the call, will use a default, predetermined value.

Echo The PHP command that specifies what text content will be left in place of a PHP container of code. The echo command returns nothing and is slightly faster than the print command.

Print
The PHP command that specifies what text content will be left in place of a PHP container of code. The print command returns a value of 1 and is slightly slower than the echo command.

Key Indicator Similar to the index indicator of an array used to refer to an individual element within the array, the string-based value used to refer to an object’s attribute.

$_POST The object containing all of the information that was submitted from an HTTP POST request, typically used to retrieve data from a submitted web form.

$_GET The object containing all of the information that was submitted from an HTTP GET request.

Payload The portion of an HTTP request that contains the actual data being communicated.

Counter-Controlled Loop A loop that terminates after the loop has completed a predetermined number of iterations. 
Sentinel-Value-Controlled Loop A loop that terminates when the specific sentinel value is detected

XML (Extensible Markup Language) A markup language that provides rules to define simple and complex data structures. 
JSON (JavaScript Object Notation) An open standard file format and data interchange format that uses human-readable text to store and transmit data.

Cookie A small text file created by a webserver and stored on a client’s system to identify the client. 
Web Storage Storage that resides within a client’s browser and is available to websites and web applications.

Session Cookie A cookie that does not have a set expiration time and expires when the user closes the browser window or tab. 
Persistent Cookie A cookie that has a set expiration time and remains on the client’s system until that time.

Third-Party Cookie A cookie created by an organization other than the one that owns the website that the user is visiting.

example of a third party cookie:

you just visited Amazon and
looked at a particular pair of shoes, and after navigating to a completely different website, you now see an ad for those exact shoes.

--

Session Storage Data that is created and stored on the client’s system by JavaScript and only remains on the system until the browser window or tab is closed. 
Local Storage Data that is created and stored on the client’s system by JavaScript and remains on the system indefinitely until the client removes it.

File Stream Object A programming object that represents the data going into or being read out of a digital file. Also called file pointer.

Backward Compatibility The ability of new software or hardware to support software or hardware that was created using older versions of the same software or hardware.

Serialize The process of converting programming objects and data structures into the plain-text equivalent for long-term storage. 
Deserialize The process of converting serialized plain-text data into the programming equivalent in the memory.

Database Management Systems (DBMS) Software designed to maintain access to some form of data storage, either relational or nonrelational.

Relational Database A model of data storage that stores similar data within related tables of data. 
No-SQL Database A model of data storage that uses alternative methods of storing and organizing data.

Database Schema The definition of a database structure.

Future-Proof A development approach or technique that helps ensure something will remain usable in the future and as other things change and evolve.


Risk Management The continuing process of identifying, analyzing, evaluating, and treating exposure to loss and monitoring the risk controls and financial resources required to mitigate any impact on the organization. 
Risk Assessment The process of identifying potential hazards and analyzing what could happen if the hazard or disaster occurred

CIA Triad A common model that forms the basis for the development of security systems and includes the facets of :

1. Confidentiality The state of keeping information private and preventing access to those who are not authorized to view the information.

2. Integrity In computer science, the state of being authentic and unaltered. 
3. Availability The state of being on and accessible to users.

--

Risk Analysis The process of identifying and analyzing potential issues that could negatively impact business operations, projects, or assets.

Validation The process of ensuring that only the correct type of data is entered into the correct field. 
Sanitization The process of detecting potentially malicious code placed inside of a form field and rendering it ineffective in order to prevent XSS attacks.

Authentication Token A digital file that serves as proof of authentication and can be used to access one or more systems without havidng to reauthenticate each time.

DOMPurify A free JavaScript API that utilizes DOM-only features to help prevent XSS attacks through sanitization.


