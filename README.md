# Blackboard Cloud Services Engineering Assignment

Write solutions for at least one of the following two problems, using any language you like. Push your changes to a public github repository.

# Exercise 1: Pascal’s Triangle  

The following pattern of numbers is called Pascal’s triangle.

        1  
       1 1  
      1 2 1  
     1 3 3 1   
    1 4 6 4 1  
       ...  

The numbers at the edge of the triangle are all 1, and each number inside the triangle is the sum of the two numbers above it. Write a function that computes the elements of Pascal’s triangle by means of a recursive process.

Do this exercise by implementing a pascal function, which takes a column c and a row r, counting from 0 and returns the number at that spot in the triangle. For example, 

>pascal(0,2)=1, pascal(1,2)=2 and pascal(1,3)=3.

    def pascal(c: Int, r: Int): Int  

#Exercise 2: Parentheses Balancing  

Write a solution which verifies the balancing of parentheses in a string. For example, the function should return true for the following strings:

>(if (zero? x) max (/ 1 x))  

>I told him (that it’s not (yet) done). (But he wasn’t listening)  

The function should return false for the following strings:

>:-)  

>())(  

The last example shows that it’s not enough to verify that a string contains the same number of opening and closing parentheses.

Do this exercise by implementing a balance function. Its signature (in Scala) is as follows:

    def balance(chars: List[Char]): Boolean


