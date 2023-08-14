# Computational Complexity
 
 The time and space (memory) required to execute an algorithm. More spcifically, the rate of growth as the size of the input increases
 
## Ok but why?
 
1. Better grasp of performance as __the input__ scales
2. Make better decisions by understanding the efficiency and tradeoffs between different algorithms and data structures
3. Optimization of a solution
4. Pass that technical interview!
 
## Asymptotic Notation
 
 Quantifies the run time as the input approaches infinity
 
 Big O - Upper Bound - Worst Case Scenario
 Big-Omega - Lower Bound - Best Case Scenario
 Big Theta - Tight Bound
 
## Evaluation
 - What input is scaling?
 - How does that affect the number of computations for time complexity or allocated memory for space complexity?
 - Are there nested loops? You may need to multiply
 - Understand the underlying complexity of helper methods and data structure operations.
 - Remember to drop coefficients and lower order terms
 - Are there multiple inputs?
  - Distinguish the factors from one another by using different variables
  - Evaluate them one at a time by holding the others constant 
 
## Time Complexity of Data Structures

Think of these as the building blocks of an algorithm.

It is useful to remember the basic operations of __arrays__, __hash tables__, __linked list__, and __trees__. Basic Operations incliude:
 
 - __Access__ing a specific value
 - __Search__ing for a value
 - __Insert__ing a value anywhere
 - __Delete__ing a value from anywhere
 
 
## Space Complexity
 
 Does it include the input? Yes and No
 
### Auxiliary Space vs Space Complexity
 
 Aux Space - measures the extra memory needed to perform an algorithm
 Space - measures aux space and the size of the input
 
 We are typically measuring **aux space**.
 
## Common Big-O Orders

**This list is not exhaustive**

- Constant - O(1)
 - Independent of input size
 - Examples:
   - Lookup a key in a hashtable
   - Assigning a value
   - Arithmetic calculation
- Logarithmic - O(log n)
 - Grows logarithmically to input size
 - Examples
  - Binary search in sorted array
  - inserting value into a binary search tree
- Linear - O(n)
 - Grows proportional to input size
 - Examples
  - Looping through a collection of elements
  - Finding an item in the linked list or array
- Quasilinear - O(n log n) 
 - Common for comparison sorting algorithms
 - Examples
  - Mergesort
  - Quicksort
  - Heapsort
- Quadratic - O(n^2)
 - Grows proportional to the square of the input size
 - Examples
  - nested loop
  - iterating through a matrix
  - Insertion Sort
- Polynomial - O(n^c)
 - C is some constant power
 - Example
  - Deeply Nested Loop
- Exponential - O(c^n)
 - C is a constant base
 - Example
  - Multiple recursion algorithms
- Factorial - O(n!)
 - Grows proportional to the factorial of the input size
 - Examples
  - Finding premutations
  - Brute force traveling salesman
  
## Resources

- https://www.bigocheatsheet.com/
- https://www.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/asymptotic-notation