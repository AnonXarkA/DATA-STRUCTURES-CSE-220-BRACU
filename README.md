# DATA-STRUCTURES-CSE-220-BRACU

# LAB ASSIGNMENTS

<h3 align="left">Languages:</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


# LAB 1 - Arrays 📝

1. Shift Left k Cells   
Consider an array named source. Write a method/function named shiftLeft( source, k) that shifts all the elements of the source array to the left by 'k' positions. You must execute the method by passing an array and number of cells to be shifted. After calling the method, print the array to show whether the elements have been shifted properly.
Example:
source=[10,20,30,40,50,60]
shiftLeft(source,3)
After calling shiftLeft(source,3), printing the array should give the output as: 
 [ 40, 50, 60, 0, 0, 0 ]

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%201.py">Task 1</a> <br>


2. Rotate Left k cells 
 Consider an array named source. Write a method/function named rotateLeft( source, k) that rotates all the elements of the source array to the left by 'k' positions. You must execute the method by passing an array and number of cells to be shifted. After calling the method, print the array to show whether the elements have been shifted properly.
Example:
source=[10,20,30,40,50,60]
rotateLeft(source,3)
After calling rotateLeft(source,3), printing the array should give the output as: 
 [ 40, 50, 60, 10, 20, 30]

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%202.py">Task 2</a>  <br>

3. Remove an element from an array
 Consider an array named source. Write a method/function named remove( source, size, idx) that removes the element in index idx of the source array. You must execute the method by passing an array, its size and the idx( that is the index of the element to be removed). After calling the method, print the array to show whether the element of that particular index has been removed properly.
Example:
source=[10,20,30,40,50,0,0]
remove(source,5,2)
After calling remove(source,5,2) , printing the array should give the output as: 
 [ 10,20,40,50,0,0,0]

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%203.py">Task 3</a> <br>

4. Remove all occurrences of a particular element from an array
Consider an array named source. Write a method/function named removeAll( source, size, element) that removes all the occurrences of the given element in the source array. You must execute the method by passing an array, its size and the element to be removed. After calling the method, print the array to show whether all the occurrences of the element have been removed properly.
Example:
source=[10,2,30,2,50,2,2,0,0]
removeAll(source,7,2)
After calling removeAll(source,7,2), all the occurrences of 2 must be removed. Printing the array afterwards should give the output as: 
 [ 10,30,50,0,0,0,0,0,0]
 
Ans: ⚡  <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%204.py">Task 4</a> <br>

5. Splitting an Array
Suppose the elements of an array A containing positive integers, denote the weights in kilograms. And we have a beam balance. We want to put the weights on both pans of the balance in such a way that for some index 0 < i < A.length - 1, all values starting from A[0], A[1], upto A[ i - 1], should be on the left pan. And all values starting from A[ i ] upto A[ A.length - 1] should be on the right pan and the left and right pan should be balanced. If such an i exists, return true. Else, return false. 
Input: [1, 1, 1, 2, 1]	Output : true
Explanation: (summation of [1, 1, 1] = summation of [2,1])
Input: [2, 1, 1, 2, 1] Output: false
Input: [10, 3, 1, 2, 10]  Output: true 
Explanation: (summation of [10, 3] = summation of [1,2,10]))

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%205.py">Task 5</a> <br>

6. Array series
Write a method that takes an integer value n as a parameter. Inside the method, you should create an array of length n squared (n*n) and fill the array with the following pattern. Return the array at the end and print it.
If,
n=2: { 0,1,   2,1 } (spaces have been added to show two distinct groups).
n=3 : { 0, 0, 1,    0, 2, 1,    3, 2, 1 } ((spaces have been added to show three distinct 
groups).
n=4 : {0, 0, 0, 1,   0, 0, 2, 1,    0, 3, 2, 1,   4, 3, 2, 1}  (spaces have been added to show four distinct groups).

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%206.py">Task 6</a> <br>

7. Max Bunch Count
A "bunch" in an array is a consecutive chain of two or more adjacent elements of the same value. Write a method that returns the number of elements in the largest bunch found in the given array.
Input: [1, 2, 2, 3, 4, 4, 4]   Output: 3
Explanation: There are two bunches here {2,2} and {4,4,4}. The largest bunch is {4,4,4} containing 3 elements so 3 is returned.
Input: [1,1,2, 2, 1, 1,1,1] Output:4
 Explanation: There are three bunches here {1,1} and {2,2} and {1,1,1,1}. The largest bunch is {1,1,1,1} containing 4 elements so 4 is returned.

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%207.py">Task 7</a> <br>
 
8. Repetition
 Write a method that takes in an array as a parameter and counts the repetition of each element. That is, if an element has appeared in the array more than once, then its ‘repetition’ is its number of occurrences. The method returns true if there are at least two elements with the same number of ‘repetition’. Otherwise, return false.
Input: {4,5,6,6,4,3,6,4} Output: True
Explanation: Two numbers repeat in this array: 4 and 6. 4 has a repetition of 3, 6 has a repetition of 3. Since two numbers have the same repetition output is True.
Input: {3,4,6,3,4,7,4,6,8,6,6} Output: False
Explanation: Three numbers repeat in this array:3,4 and 6 .3 has a repetition of 2, 4 has a repetition of 3, 6 has a repetition of 4. Since no two numbers have the same repetition output is False.

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%208.py">Task 8</a> <br>

9. Circular Array
NB: You need to implement circular arrays to solve the following problems. You cannot convert them to linear arrays.
 Palindrome
Write a method/function that takes in a circular array, its size and start index and finds whether the elements in the array form a palindrome or not. Return true if the elements form a palindrome, otherwise, return false.
Example:

Input: [20,10,0,0,0,10,20,30] (start =5, size=5) Output: True.

Input:[10,20,0,0,0,10,20,30] (start =5, size=5) Output: False

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%209.py">Task 9</a> <br>

10. Intersection
Write a method/function that takes two circular arrays, their sizes and start indexes and returns a linear array containing the common elements between the two circular arrays.
Input: 
Circular array 1 : [40,50,0,0,0,10,20,30] (start_1 =5, size_1 =5)
[10 20 30 40 50]
Circular array 2 : [10,20,5,0,0,0,0,0,5,40,15,25] (start_2=8, size_2 =7)
[5 40 15 25 10 20 5]
Output:[10,20,40]

Ans: ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%2010.py">Task 10</a> <br>

11. Suppose you have been hired to develop a musical chair game. In this game there will be 7 participants and all of them will be moving clockwise around a set of 7 chairs organized in a circular manner while music will be played in the background. You will control the music using random numbers between 0-3.If the generated random number is 1, you will stop the music and if the number of participants who are still in the game is n, the participants at position (n/2) will be eliminated. Each time a participant is eliminated, a chair will be removed and you have to print the player names who are still in the game.The game will end when there will be only one participant left. At the end of the game,display the name of the winner.
[Hint: You will need to invoke a method to generate a random number between 0
(inclusive) to 3 (inclusive)]

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%201/task%2011.py">Task 11</a> <br>



# LAB 2 - Linked list  📝

 Linked List
Task 1:
i) Create a Node class which will hold two fields i.e an integer element and a reference to the next Node.
ii) Create a Linked list Abstract Data Type (ADT)named MyList.The elements in the list are Nodes consisting of an integer type key (all keys are unique) and a reference to the next node.
[You are not allowed to use any global variable other than head]

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%202/task%201.py">Task 1</a> <br>

Task 2: (Basic operations) 20 marks
Constructor:

a.  	MyList (int [] a) or def __init__ (self, a)  (5)

Pre-condition: Array cannot be empty.
Post-condition:This is the default constructor of MyList class. This constructor creates a list from an array.


void showList ( ) or def showList(self) (2)

Precondition: None.
Postcondition: Outputs the keys of the elements of the order list. If the list is empty, outputs “Empty list”.
boolean isEmpty ( ) or def isEmpty(self) (1)

Pre-condition: None.
Post-condition: Returns true if a list is empty. Otherwise, returns false.
void clear ( ) or def clear(self) (1)

Pre-condition: The list is not empty.
Post-condition: Removes all the elements from a list.

void insert (Node newElement) or def insert(self, newElement) (3)
Pre-condition: None.
Post-condition: This method inserts newElement at the tail of the list. If an element with the same key as newElement already exists in the list, then it concludes the key already exists and does not insert the key.

void insert (int newElement, int index) or def insert(self, newElement, index) (4)

Pre-condition: The list is not empty.
Post-condition: This method inserts newElement at the given index of the list. If an element with the same key as newElement value already exists in the list, then it concludes the key already exists and does not insert the key. [You must also check the validity of the index].
Node remove (int deleteKey) or def remove(self, deletekey) (4)
Pre-condition: List is not empty.
Post-condition: Removes the element from a list that contains the deleteKey and returns the deleted key value.

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%202/Task%202.py">Task 2</a> <br>

Task 3: (Advanced operations) (20 marks)
 
Write a function to find out the even numbers that are present in the list and output another list with those numbers. (3)

Sample Input
Sample Output
1 -> 2 -> 5 -> 3 -> 8
2 -> 8
101 -> 120 -> 25 -> 91-> 87 -> 1
120


Write a function to find out if the element is in the list or not. (3)

Sample Input
 Sample Output
1 -> 2 -> 5 -> 3-> 8 and 7
False
101 -> 120 -> 25 -> 91-> 87 -> 1 and 87
True


Write a function to reverse the list. [You are not allowed to create any other list] (3)

Sample Input
Sample Output
1 -> 2 -> 5 -> 3-> 8
8 -> 3 -> 5 -> 2 -> 1


Write a function to sort the list. [You are not allowed to create any other list] (3)

Sample Input
Sample Output
1 -> 2 -> 5 -> 3-> 8
1 -> 2 -> 3 -> 5 -> 8




Write a function that prints the sum of the values in the list. (4)

Sample Input
Sample Output
1 -> 2 -> 5 -> 3-> 8
19


Write a function that rotates the elements of the list k times. [You are not allowed to create any other list]. (4)
Sample Input
Sample Output
3 -> 2 -> 5 -> 1-> 8, left, 2
5 -> 1 -> 8 -> 3 -> 2
3 -> 2 -> 5 -> 1-> 8, right, 2
1 -> 8 -> 3 -> 2 -> 5

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%202/task%203.py">Task 3</a> <br>

# LAB 3 - Doubly Linked List 📝

1. i) Create a Node class which will hold three fields i.e an integer element and a reference to the next Node along with a reference to the previous Node.
ii) Create a Dummy Headed Doubly Circular Linked list Abstract Data Type (ADT)named DoublyList.The elements in the list are Nodes consisting of an integer type key (all keys are unique) and a reference to the next node and a reference to the previous Node.
[You are not allowed to use any global variable other than head.]

2. (Basic operations) (20 marks)
Constructors: (3)
a.  	DoublyList (int [] a) or def __intit__(self,a)

Pre-condition: Array cannot be empty.
Post-condition:This is the default constructor of MyList class. This constructor creates a Dummy Headed Doubly Circular Linked list list from an array.


void showList ( ) or def showList(self) (1)

Precondition: None.
Postcondition: Outputs the keys of the elements of the order list. If the list is empty, outputs “Empty list”.

void insert (Node newElement ) or def insert(self, newElement) (4)
Pre-condition: None.
Post-condition: This method inserts newElement at the tail of the list. If an element with the same key as newElement already exists in the list, then it concludes the key already exists and does not insert the key.

void insert (int newElement, int index) or def insert(self, newElement, index) (4)

Pre-condition: The list is not empty.
Post-condition: This method inserts newElement at the given index of the list. If an element with the same key as newElement value already exists in the list, then it concludes the key already exists and does not insert the key. [You must also check the validity of the index].

void remove (int index) or def remove(self, index)  (4)

Pre-condition: The list is not empty.
Post-condition: This method removes the Node at the given index of the list.[You must also check the validity of the index].
int removeKey(int deleteKey) or def removeKey(self, deletekey) (4)
Pre-condition: List is not empty.
Post-condition: Removes the element from a list that contains the deleteKey and returns the deleted key value.
 
Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%203/task1%2B2.py">Task 1+2</a> <br>

# LAB 4 - Stack-Parenthesis Balancing 📝

Input
Your program will take an arithmetic expression as a String input. For Example:
 
“1+2*(3/4)”
 
“1+2*[3*3+{4–5(6(7/8/9)+10)–11+(12*8)]+14”
 
“1+2*[3*3+{4–5(6(7/8/9)+10)}–11+(12*8)/{13+13}]+14”
 
Program
 
Your program will determine whether the open brackets (the square brackets, curly braces and the parentheses) are closed in the correct order.
 
Outputs:
 
Output 1
 
1+2*(3/4)
This expression is correct.
 
Output 2
 
1+2*[3*3+{4–5(6(7/8/9)+10)–11+(12*8)]+14
This expression is NOT correct.
Error at character # 10. ‘{‘- not closed.
 
Output 3
 
1+2*[3*3+{4–5(6(7/8/9)+10)}–11+(12*8)/{13+13}]+14
This expression is correct.

Output 4
 
1+2]*[3*3+{4–5(6(7/8/9)+10)–11+(12*8)]+14
This expression is NOT correct.
Error at character # 4. ‘]‘- not opened.
Task 1
Solve the above problem using an array based stack.

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%204/Task%201.py">Task 1</a> <br>
 
Task 2
Solve the above problem using a linked list based stack.

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%204/Task%202.py">Task 2</a> <br>

# LAB 5 - Recursion 📝

Assignment Tasks: 
1. [Very Easy] [5 Marks each] 

Implement a recursive algorithm to find factorial of n.   

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%201%20a.py">Task 1 A</a> <br>

Implement a recursive algorithm to find the n-th Fibonacci number. 

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%201%20b.py">Task 1 B</a> <br> 

Print all the elements of a given array recursively.

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%201%20c.py">Task 1 C</a> <br> 

Given base and n that are both 1 or more, compute recursively (no loops) the value of base  to the n power, so powerN(3, 2) is 9 (3 squared). 
powerN(3, 1) → 3 
powerN(3, 2) → 9 
powerN(3, 3) → 27 

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%201%20d.py">Task 1 D</a> <br>

2. [Easy] [5 Marks each] 
a)Implement a recursive algorithm that takes a decimal number n and converts n to its corresponding (you may return as a string) binary number.

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%202%20a.py">Task 2 A</a> <br> 

b) Implement a recursive algorithm to add all the elements of a non-dummy headed singly linked linear list. Only head of the list will be given as parameter where you may assume every node can contain only integer as its element.
Note: you’ll need a Singly Node class for this code.

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%202%20b.py">Task 2 B</a> <br> 

c) Implement a recursive algorithm which will print all the elements of a non-dummy headed singly linked linear list in reversed order.
Example: if the linked list contains 10, 20, 30 and 40, the method will print
40
30
20
10
Note: you’ll need a Singly Node class for this code.

Ans:  ⚡  <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%202%20c.py">Task 2 C</a> <br>

3. [Medium] [8 Marks] 


Suppose, you have been given a non-negative integer which is the height of a ‘house of  cards’. To build such a house you at-least require 8 cards. To increase the level (or height)  of that house, you would require four sides and a base for each level. Therefore, for the top  level, you would require 8 cards and for each of the rest of the levels below you would  require 5 extra cards. If you were asked to build level one only, you would require just 8 cards. Of course, the input can be zero; in that case, you do not build a house at all.  Complete the recursive method below to calculate the number of cards required to build  a ‘house of cards’ of specific height given by the parameter. 

public int hocBuilder (int height){ 
// TO DO 
} 
OR 
def hocBuilder(height): 
#TO DO 

Ans:  ⚡  <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%203.py">Task 3</a> <br>


4. [Hard] [ 10 + 10 = 20 Marks]
 a. Print the following pattern for the given input (you must use recursion): Sample Input: 5 
Sample Output:
1

1 2

1 2 3

1 2 3 4

1 2 3 4 5

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%204%20a.py">Task 4 A</a> <br>

b. Print the following pattern for the given input (you must use recursion): Sample Input: 5 
Sample Output: 

        1

      1 2

    1 2 3

  1 2 3 4

1 2 3 4 5

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%204%20b.py">Task 4 B</a> <br>

5. [Very Hard] [12 Marks] Suppose, you are working in a company ‘X’ where your job is to calculate the profit based  on their investment.  
If the company invests 100,000 USD or less, their profit will be based on 75,000 USD as  first 25,000 USD goes to set up the business in the first place. For the first 100,000 USD,  the profit margin is low: 4.5%. Therefore, for every 100 dollar they spend, they get a profit  of 4.5 dollar. 
For an investment greater than 100,000 USD, for the first 100,000 USD (actually on 75,000  USD as 25,000 is the setup cost), the profit margin is 4.5% where for the rest, it goes up to  8%. For example, if they invest 250,000 USD, they will get an 8% profit for the 150,000  USD. In addition, from the rest 100,000 USD, 25,000 is the setup cost and there will be a  4.5% profit on the rest 75,000. Investment will always be greater or equal to 25,000 and  multiple of 100. 
Complete the RECURSIVE methods below that take an array of integers (investments)  and an iterator (always sets to ZERO(‘0’) when the method is initially called) and prints  the profit for the corresponding investment. You must avoid loop and multiplication (‘*’)  operator. 
public class FinalQ{ 
 public static void print(int[]array,int idx){ 
if(idx<array.length){ 
 double profit=calcProfit(array[idx]); 
 //TODO 
} 
 } 
 public static double calcProfit(int investment){ //TODO 
 }



 public static void main(String[]args){ 
int[]array={25000,100000,250000,350000}; 
print(array,0); 
 } 
}



OR 
class FinalQ: 
 def print(self,array,idx): 
 if(idx<len(array)): 
 profit = self.calcProfit(array[idx])  #TO DO 
  
 def calcProfit(self,investment): 
 #TO DO 
  
#Tester 
array=[25000,100000,250000,350000] 
f = FinalQ() 
f.print(array,0)



------------------------------------------------- 
Output: 
1. Investment: 25000; Profit: 0.0 
2. Investment: 100000; Profit: 3375.0 
3. Investment: 250000; Profit: 15375.0 
4. Investment: 350000; Profit: 23375.0 

Ans:  ⚡ <a href="https://github.com/AnonXarkA/DATA-STRUCTURES-CSE220-BRACU/blob/main/LAB%205/Task%205.py">Task 5</a> <br>






