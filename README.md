# algorithmic-techinical-questions-examples
1. Repeat the problem statment a few times in your head - clarifyig (with your interviewer) any unknown terms or unclear clauses in the problem statement

2. Jot down key pieces of information : input domain (numbers,strings,etc..) whether or not the inputs are sorted. the type of data structure that we are dealing with
   (Binay search tree or not, singly or doubly linked list, a single or multi dimenstional array) , a suggested traversal method (breadth-first or depth first), or desired 
    implementation style
	
3. Actively think about edges cases (i.e inputs that could break your solution) to clarify with the interviewer and run through when testing solution you decide to run

4. Acknowledge the brute-force solution 

5. Analyze the (usually quadratic factorial, or exponential) time (typically constant) and space complexcity of the brute-force approach
6. think about a solution that optimizes for time complexity (i.e use more space for time saving) . I usually ask myslef what are the redundant computations or what can i store( and in which data structure)
   in reduce to the workload
7 Think about a solution that optimizes for space complexcity (i.e takes longer to run but uses less space) , it will hopfully be more efficient (in time complexcity) than
   the brute-force approach. if we are dealing with list of inputs , i usually ask myslef : is there a way to (in-place) sort the inputs (if they are not already sorted) to achieve o(nlogn) runtime with space o(1)
   ? Or is there a way of using a few variables/pointers while iterating to achieve an O(n) time and o(1) space solution?
8  Avoid commiting to any solution --- leaving a little time to see if any other approaches to come to mind. Typically, the current problem resembles another problem
    that u have solved and a technique used in that solved problem can be applied
9	Ask the interviewer what we are optimizing for and narrow down your set of solutions to a single one to code

10 Outline the structure of the solution : either with high level functions (input,purpose of the method , and it output) or the order of loops and conditions

11 Start writing code 

12 Do a little pass code for review of my solution making sure it is syntactically correct and not introducing idioms that utilize extra space/time (i.e creating intermediate arrays or doing implicit passes through entire array)

13 Run through your code with normal edge-case inputs --correcting any bugs in solution

14 if there is follow-up tweak to the original problem.think about how to reuse the previosuly implemented methods to implement the tweak

15. Apply the same principles of analysis from the list to the follow-up question's solution
