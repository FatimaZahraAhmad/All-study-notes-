NOTES FOR JAVA - #:



Java virtual machine (JVM)
A platform allowing java programs to run on any device operating system

Replit - a IDE mainly used for java


java Development Kit (JDK)
A software package giving you all the core language files to start coding in java.

java statements and java methods
Java statements are instructions that tell the program what to do.

Java methods are blocks of codes that perform tasks.


Integrated Development Environment (IDE)
A software which gives developers the tools needed to work with java code, 

one widely used IDE for java is "Eclipse".


The steps to  writing a program are:

1. Understand unsolved problem.
2. Design solution.
3. Draw flow chart.
4. Write pseudo-code.
5. Write code.
6. Test & debug.
7. Test with real-world users.
8. Release program.
9. Iterate the steps for the next version.



Word processor / text editor
A software text editor that you can type code in plain English. 
you can convert the text / Pseudo-Code into a extension such as .py, or .js, etc, etc.



Syntax highlighting
A way of coloring different text in code to make it easier to understand.


Pseudo-Code
A way of writing in English in short phrases to write code for programs before actually creating it.


Comments 
a way to write notes for yourself or explanations for other programmers within your code,
being ignored by the compiler, only readable to humans.

ways of writing comments:
      Single-Line:

// comments

      Multi-Line:

/* the beginning
of a cool
multi-line comment */

      Doc-Comments:

/** doc 
comments */


Javadoc
a program of the Java Development Kit (JDK) and converts doc comments into an external file.


While loop
A statement performing an action until a certain criteria is false using a boolean value of 0/1.

    indefinate loop
    A loop where you dont know when its going to end/stop.
    infinite loop
    A loop that goes forever until your computer crashes or you escape.



function syntax:

<body>
}
public static void main()

private - only inside the same class

public - accesible anywhere

static - belongs to a class not objects

abstract - has no body and must be implemented by a subclass

void - no return value

compiler
a program that converts code into computer readable statements.



main method - the entry point of a java program where the program starts running.
without it a normal java program cannot progress.



The five basic concepts of OOD, object oriented design:
Classes/objects,

Encapsulation/data hiding,

Inheritance, 

Polymorphism,

Interfaces/methods.


Classes/objects - A object is an instance of a class, a class being the blueprint.

Encapsulation/data hiding - A word that describes protection or hiding of data.

Inheritance - A object or an instance inheriting their parents methods.
 what operations can be done, not how they are done.

ADT/ abstract data types - A model of idea of how data should behave,
Binding - The association between method and class

Override - overrides, or, changes a method from the parent class.

round robin - A scheduling algorithm that points to a circular route of lists, originally being a concept of circularly lists.

algorithm analysis 
a technique that's used to measure the performance of the algorithms


asymptotic notations
a set of mathematical notations introduced to understand the run-time performances of algorithims.
the three main asymptotic notations are:

    Big Oh (O)
    Measures the upper bound (worst case or maximum time)

    Omega (Ω)
    Measures lower bound (best-case or minimum time)

    Theta (θ)
    Measures both upper and lower bound.
---

Analysis of Algorithmic Functions
Analysis of algorithms helps to predict the resources that an algorithm will take to nish execution. A common way to
represent how long an algorithm will take to execute is the Big O notation, some include:


O(1)
Name - Constant Time
Always takes the same time, No matter what input size.

O log (n)
Name - Logarithimic Time
Time grows slowly, Even for large data.

O(n)
Name - Linear Time
Time grows directly with input size.

O(n log n)
Name - Log-linear Time
Common for efficient sorts.

O(n^2)
Name - Quadratic Time
Time grows fast in nested loops.

O(n^n)
Name - Cubic function
increases in size as the size of the
iterations n increases, the n being the "^n" in the formula. One similar term is : 
    
    Polynomial Algorithm - represents an operation that increases in size
                           as the size of the iterations n increases.

Simple justication techniques 
The methods that determine the correctnes of an algorithm
and identify how fast or slow it is. There are various techniques, including :

    Contra attack -
                   Contradiction:
                   Contrapositive: 

    Induction - Proving that an algorithm works for all inputs.

    Loop variants - Proving that a loop in an algorithm ends/terminates at one point.
                    (e.g: while n > 0, minus n by one.   this proves n WILL go to 0 and terminate, even if we dont know when.)


recursion - a function that calls itself

iteration - looping through the code block

Fibonacci Series
list of numbers where the next number in the series is the sum of the
previous 2. e.g:
1, 1, 2, 3, 5, 8



Tower of Hanoi
A game about disks and pegs where we have to move the disks to another place.

Binary search / Divide and conquer
A Method of searching for something in an array by dividing it in half, searching for the required item, and retrieving it.
e.g: 
Array = [2, 5, 8, 12, 16, 23].
we want to find 12.
middle element = 8.     12 > 8, so search the right half [12, 16, 23]
new middle = 16.        12 < 16, so search the left half. [12].
12 = 12, so the element needed has been found.


Sequential Search
A way of searching in a linear fashion, (Being the reason its also called linear search)
checking each element one by one untill you find the target value, or reach the end.

Exponential Search
A way of searching in a exponential fashion, squaring each index after not finding the value needed. e.g:
Array : [2, 3, 4, 10, 15, 18, 21, 24, 27, 30], we need to find 21.
1. start at index 0 - 2  not 21.
2. check arr[1] = 3.
3. check arr[2] = 4
4. check arr[4] = 15
5. check arr[8] = 27. (27 > 21, so we stop. now we know 21 is between index four and eight, so we apply a binary search there.)

Modulo (x % y)
A operation giving the remainder after diving a number by another.



Stack
A linear data structure following the LIFO rule, imagine a stack of plates.
e.g: you put a plate on top (push) and take a plate from the top (pop)

Queue
A linear data structure following the FIFO rule, imagine a line of people.
e.g: people come in the line, getting added. 
    the first person to arrive at the counter is served first.


Double Ended Queue / Deque
A mix of stack and queue.

Dynamic Array
a set of mathematical notations introduced to understand the run-time performances of algorithims.
the three main asymptotic notations are:

    Big Oh (O)
    Measures the upper bound (worst case or maximum time)

    Omega (Ω)
    Measures lower bound (best-case or minimum time)

    Theta (θ)
    Measures both upper and lower bound.
---

Analysis of Algorithmic Functions
Analysis of algorithms helps to predict the resources that an algorithm will take to nish execution. A common way to
represent how long an algorithm will take to execute is the Big O notation, some include:


O(1)
Name - Constant Time
Always takes the same time, No matter what input size.

O log (n)
Name - Logarithimic Time
Time grows slowly, Even for large data.

O(n)
Name - Linear Time
Time grows directly with input size.

O(n log n)
Name - Log-linear Time
Common for efficient sorts.

O(n^2)
Name - Quadratic Time
Time grows fast in nested loops.

O(n^n)
Name - Cubic function
increases in size as the size of the
iterations n increases, the n being the "^n" in the formula.

    polynomial algorithm 
    represents an operation that increases in size
    as the size of the iterations n increases.


Simple justication techniques 
The methods that determine the correctness of an algorithm
and identify how fast or slow it is. There are various techniques, including :

    Contra attack: The use of using the contrapositive method on a statement,
    This means of proving the negative of a statement to be true.

    Induction: The use of proving the algorithm works for all inputs, especially recursive algorithms.

    Loop variants: The use of proving that a loop in an algorithm terminates.
    (e.g: while n > 0, minus n by one.   this proves n WILL go to 0 and terminate, even if we dont know when.)


recursion - a function that calls itself

iteration - looping through the code block

Fibonacci Series
A list of numbers where the next number in the series is the sum of the
previous 2. e.g:
1, 1, 2, 3, 5, 8

Tower of Hanoi
A game about disks and pegs where we have to move the disks to another place.

Binary search / Divide and conquer
A Method of searching for something in an array by dividing it in half, searching for the required item, and retrieving it.
e.g: 
Array = [2, 5, 8, 12, 16, 23].
we want to find 12.
middle element = 8.     12 > 8, so search the right half [12, 16, 23]
new middle = 16.        12 < 16, so search the left half. [12].
12 = 12, so the element needed has been found.


Sequential Search
A way of searching in a linear fashion, (Being the reason its also called linear search)
checking each element one by one untill you find the target value, or reach the end.

Exponential Search
A way of searching in a exponential fashion, squaring each index after not finding the value needed. e.g:
Array : [2, 3, 4, 10, 15, 18, 21, 24, 27, 30], we need to find 21.
1. start at index 0 - 2  not 21.
2. check arr[1] = 3.
3. check arr[2] = 4
4. check arr[4] = 15
5. check arr[8] = 27. (27 > 21, so we stop. now we know 21 is between index four and eight, so we apply a binary search there.)

Modulo (x % y)
A operation giving the remainder after diving a number by another.

Stack
A linear data structure following the LIFO rule, imagine a stack of plates.
e.g: you put a plate on top (push) and take a plate from the top (pop)

Queue
A linear data structure following the FIFO rule, imagine a line of people.
e.g: people come in the line, getting added. 
    the first person to arrive at the counter is served first.


Double Ended Queue / Deque
A mix of stack and queue.

Dynamic Array
A array that can change its size at runtime, shrink, or grow.

Constructor
A method in a class used to initialize objects.

A list where you work with positions (References to nodes)
instead of numeric indices.

Abstract Data Type (ADT)
peration allowing you to see what they do, not how they are implemented

    Double hashing - Uses a 2nd hash function to decide how far to jump next time. formula - (H1 + I * H2) % N 
    
clustering
When many keys end up close together in a hash table, usually because of collisions.

buckets
A container that holds one or more key-value pairs that hash to the same index.

modular hashing
using the modulus operator (%) to fit the turned number (hash) into the table size range.

hashing
a technique that turns a key into a number (hash) to find where to store it.

chaining
When 2 or more keys get the same hash index we store all items
together in a linked list at that index.

robin hood hashing
A collision strategy that evens out probe distances by
letting new keys "Steal" Slots from keys closer to their ideal position,
improving fairness and consistency.

probe counts
The number of attempts (or, probes) made to find an empty slot or key in the existing bucket.


organ-pipe search
A technique to arrange data so that frequently searched items are near the CENTER of the list,
and the less used ones at the edges,
its name coming from the access pattern looking like the shape of organ pipes!

smart search 
Self-organizing algorithms that modify a list after each search to make future searches faster. 


map interface
A java.util package representing a collection of key-value pairs! it defines how maps should behave,
but doesnt exactly provide a implementation, making it a Abstract Data Type!

Lambda function
A short anonymous function your able to pass around, mostly to implement a functional interface!

Here is a list of additional map structures!  :

    TreeMap - A sorted map storing keys in ascending order (By natural ordering or a custom comparator.)

    EnunMap -  A specialized Map for use with enum keys only.

    IdentityHashMap - A map that uses object reference (==) instead of equals() to compare keys.

    LinkedHashMap - A HashMap with a linked list running through all entries.

    WeakHashMap - A map where keys are stored as weak references - 
    if a key is no longer referenced elsewhere, it can be garbage collected automatically.




A list of methods part of the NavigableMap :

    Floorkey(key) - Returns the greatest key Less than or equal to the given key.
 To start the rst pass
    CeilingKey(key) - Returns the smallest key greater than or equal to the given key.

    higherKey(key) - Returns the greatest key < the given key (Strictly only less than)

    lowerKey(key) - Returns the smallest key > the given key (Strictly only greater than)


subMap(fromKey, toKey)
A method that extracts a view of a key range from a TreeMap
which can be inclusive or exclusive. the view is live, not a copy.


Separate chaining
a method which linked lists of values are built in association with each location within the hash table when collisions occur, 
collisions being when two different keys has to the same index in a hash table.













 -- - ---- - --- - -- -- - - --   -- -  - - - 11th folder - ---- -- - -- - - -- --  -- - - -- -














Binary Search Tree (BST)
A kind of binary tree where each node follows these rules :

    The left child should be smaller then the parent node.
    The right child should be bigger then the parent node.
    Both left and right subtrees should also be BSTS.


Binary Search Key
The value  your looking for during a binary search or inside a binary search tree.


Sort map 
a searchable collection of elements, Where the elements are characterized by a unique identifier which is associated with an element.

Recursive Algorithim 
A series of program steps that repeats itself until the final result is achieved.

image keys :
    Black Nodes - May match the search key
    Grey Nodes - Will not match the search key

Search Miss
When a search key isnt in the tree.

AVL Trees
A Self-Balancing binary search tree, using rotations to rebalance when inserting or deleting :
    LL - right rotation 
                       Node added to left of left child.     fixes the right rotation
    RR - left rotation
                       Node added to right of right child.   fixes the left rotation 
    LR - left + right rotation
                       Node added to right of left cild.     fixes the left-right rotation (2 steps)
    RL - right + left notation
                       Node added to left of right child.    fixes the right-left rotation (2 steps)

The Balance Factor
A factor that measures the difference in height between the left and right child with respect to a particular node.

Insert Operation
1. start from root
2. if new value < current node -> go left
3. if new value > current node -> go right 
4. if spot empty -> insert the new node.



Splay tree
A self balancing binary search tree,  keeping itself balanced through a
operation of moving an accessed node to the root using tree notations instead 
of storing extra balance info! :

    Zig       operation - The nodes parent is the root, a single rotation brings the node to the root.

    Zig-Zag   operation - The node is a child node and its parent is a right node, or vice versa.

    Zig-Zig   operation - The node and its parent are both left / right children, two rotations are performed in the same direction.

Search Tree
A data structure used for storing data in ways making searching, insertion, and deletion efficient.

Multiway Search Trees (Also called m-ary search trees)
A generalization of a BST where each node may have more than two children.

2-3-4 Trees
A multiway search tree, balanced as all leaves are at the same depth.
its a b-tree of order four, (each node has <= 3 keys, <= 4 children.)

Self-Balancing
A BST or multiway tree that automatically keeps its height
as small as possible when inserting or deleting elements.

Red-Black Trees
A type of self balancing BST where each nodes color is either RED or BLACK.

Search Algorithm
A method used to find a specific item or piece of data within a collection,
such as a array, list, tree, or graph.

Multiway Tree / M-Way Tree
A Tree data structure where as all keaves are at the same depth its a b-tree order of four (each node has <= keys, <= 4 children)











 -- - ---- - --- - -- -- - - --   -- -  - - - 12th folder - ---- -- - -- - - -- --  -- - - -- -






Sorting Algorithm
A algorithm that helps sorting arrays

    Bubble sort
    Compares neighbors and swaps them until the list is sorted.

    Selection sort
    Picks the smallest element from the unsorted part and moves it to the sorted part. 

    merge sort
    Divides the array into two sides, sorts each side, then sticks them back together.

    Quick Sort
    Picks a random element, and moves things around so its : left-side < element > right-side.

        Partition-Exchange Sort
        Another name for Quick Sort.

    Insertion Sort
    Picks a random element, then compares it to all the other elements and sorts the array one by one.









 -- - ---- - --- - -- -- - - --   -- -  - - - 13th folder - ---- -- - -- - - -- --  -- - - -- -










brute force algorithm
 algorithm that tries every possible option until it finds a solution,

Boyer-Moore algorithm
A string search algorithm comparing the end and skipping ahead using mismatch rules


Knuth-Morris-Pratt Algorithm (KMP)
A algorithm that searches for a pattern using LPS
to avoid re-checking characters af mismatches.

    Longest Proper Prex Array (LPS)
    An array telling KMP how much the pattern has repeated in order to
    skip ahead after mismatches instead of starting over.


just imagine two shiny
  

Trie Data Structure
A tree-based data structure used to store strings, usually for fast prefix-based search.
Tries are commonly used in: autocomplete, spell checking,
prefix queries ("how many words start with X?"), routing tables, or dictionary word lookups.

    standard trie
    A trie where each character is one edge.

    compressed trie
    A trie that reduces memory by compressing chains of single-child nodes into 1 edge.

Character Array 
A list of characters stored together, often used to represent text.

Greedy Algorithm
A algorithm that follows the best path at each step without evaluating all the possible options.

Huffman's Code
An algorithm that is used for data compression where
millions of bits of data have to be compressed and stored in the most effcient manner in order
to save disk space, without any loss of data. 


 -- - ---- - --- - -- -- - - --   -- -  - - - 14th folder - ---- -- - -- - - -- --  -- - - -- -


principals office  // layout
nurses office // layout
teachers lounge // layout 
cafeteria // layout 
math // layout 
science // layout 
computer // layout 
art // layout 
plants // layout 
library //
pool 
sports
bathroom













Graph theory
The study of graphs.

    Connected graph
    A graph where all the vertices are  connected to eachother without issue.

    Disconnected graph
    A graph where some vertices are not connected to the others.

Vertices
The particular nodes in a graph.

    Isolated vertice
    A vertex with no lines connecting it to others.

    Adjacent vertice
    Connected vertices next to each other 

Degree of a vertex
This tells us how many lines are connecting one vertex to other vertices.     x


Edges
The lines that connect vertices together.

    Multiple edges
    Lines that connect the same vertices together.

    Adjacent edges
    Edges that are next to eachother.     x

Components
Subgraphs of the graph.    

Bridge
A line connecting the subgraphs together for traveling through Components.

Loop
An edge that connects a vertex to itself.

Simple graph
A graph with connection with no direction or weighted nodes.

weighted graph
A graph where each edge has a weight or cost 
(e.g: A - 5 - B , B - 2 - C , A - 8 - C)

directed graph 
A graph where every edge has an arrow pointing from one vertex to another, connecting the two.

undirected graph
A graph in which Has edges with no directions or arrows to point from.
i.e : if A is connected to B you can go both ways, as so: A - B

adjacency matrix
A grid showing what vertices connect to each others, like a who knows whom procedure.    

adjacency list
A list storing who each vertex is connected to as neighbors.    

Dijkstra's algorithm
An algorithm that finds the shortest path from start vertex to all others in weighted graph     

shortest path problem


Null graph
A graph in which there are no edges between any of its vertices.

Bipartite graph
A graph that can be split into two sets of vertices such that edges only go between sets, not within them.

Simple graph
A basic graph with restrictions:
  - No loops (vertex connected to itself)
  - No multiple edges between same vertices
  - At most one edge between any pair

Multi-graph
A graph in which there are multiple edges between any pair of vertices or there are loops.    

Planar graph
A graph that can be drawn so that all of the edges of the graph do not cross each other.

Nonplanar graph
A graph that cannot be drawn without at least one pair of its edges crossing.

cyclic grpah
a directed graph that contains a path from at least one node back to itself 

acylic graph
A graph that contains no cycle, no node can be traversed back to itself.

dense graph
a graph where almost every node is connected to many other nodes

sparse graph
a graph where most nodes are NOT connected to many other node










￼

 -- - ---- - --- - -- -- - - --   -- -  - - - 15th folder - ---- -- - -- - - -- --  -- - - -- -










your in pain!! your insane!! i can tell by what your saying!!
clock strikes 12...midnight arrives..cock your guns and pull out your knifes!! theres a grand prize...!:smirk:



Internal memory
Fast, small, temporary memory inside the workspace, losing data without power.

External memory
Slow, large, permanent memory used as hardware or usbs for the workspace, keeping data even without power.
 
internal sorting
The process of sorting all data in RAM/main memory at once.

internal merge sort
Standard merge sort where all data fits in RAM.

External memory sorting
Sorting data too large to fit in RAM, using disk storage.

multi-way merging
A process of simultaneously merging multiple sorted sequences into one sorted output.

External Memory Searching
The search of finding data in datasets too large for RAM, using disk storage.

Caches
  cache memory
  Small, fast storage that keeps copies of frequently used data so you don't have to wait for slower storage.

  web cache
  Stored website data for faster page loading

  CPU cache
  Very fast memory reducing waiting time for frequently used data

        cache hit
        CPU finds data in cache instead of slower RAM
        
        cache miss
        CPU doesn't find data in cache, must fetch from RAM


Multi-level Caches
Multiple cache layers (L1, L2, L3)
   *L1*: Fastest but smallest, closest to CPU cores
   *L2*: Slower than L1 but larger, can be private or shared
   *L3*: Slowest but largest, shared by all CPU cores

Memory management
Process of allocating memory to new objects and deallocating unused objects

Stack memory
Temporary memory for method execution and local variables, cleaned automatically

heap memory
Where Java puts objects and arrays, managed by garbage collector

garbage collector
Automatic system deleting unused objects from heap

mark and sweep algorithm
2-step process to remove unused objects
  1. Mark phase: Find objects still in use
  2. Sweep phase: Remove all unmarked objects




The amazing digital circus TADC
Hazbin hotel HH
Alien stage ALNST
Bleach
Dan da dan
Dispatch
My little pony MLP
Cooking mama


Murder drones MD
Helluva boss 




