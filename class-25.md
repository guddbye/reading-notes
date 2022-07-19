# Class Notes
# Recursion

The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function. Using a recursive algorithm, certain problems can be solved quite easily. Examples of such problems are Towers of Hanoi (TOH), Inorder/Preorder/Postorder Tree Traversals, DFS of Graph, etc. A recursive function solves a particular problem by calling a copy of itself and solving smaller subproblems of the original problems. Many more recursive calls can be generated as and when required. It is essential to know that we should provide a certain case in order to terminate this recursion process. So we can say that every time the function calls itself with a simpler version of the original problem.


approach(1) – Simply adding one by one

f(n) = 1 + 2 + 3 +……..+ n

but there is another mathematical approach of representing this,

approach(2) – Recursive adding 

f(n) = 1                  n=1

f(n) = n + f(n-1)    n>1

# What is the base condition in recursion? 
In the recursive program, the solution to the base case is provided and the solution to the bigger problem is expressed in terms of smaller problems. 
 

int fact(int n)
{
    if (n < = 1) // base case
        return 1;
    else    
        return n*fact(n-1);    
}


## pyTest

# What is PyTest?
PyTest is a testing framework that allows users to write test codes using Python programming language. It helps you to write simple and scalable test cases for databases, APIs, or UI.

# How to install PyTest
Following is a process on how to install PyTest:

Step 1) You can install pytest by

pip install pytest==2.9.1
Once the installation is complete you can confirm it with by

py.test -h
