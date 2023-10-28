# Stack
## Theory:
In C++, a stack is a fundamental data structure that adheres to the Last-In-First-Out (LIFO) principle. It resembles a stack of items, where the last one placed is the first to be removed. This versatile structure finds applications in various algorithms and data processing tasks. In C++, a stack can be implemented using arrays or linked lists. It offers essential operations like push (to add an element), pop (to remove the top element), and peek (to view the top element without removal). Understanding and effectively utilizing stacks is crucial for solving problems that require systematic data management.
![image](https://cdn.programiz.com/sites/tutorial2program/files/stack-operations.png)
### Functions:
push(element): The push function is used to add an element to the top of the stack. It increases the stack size by one and places the new element at the top.</br>

pop(): The pop function is used to remove the top element from the stack. It decreases the stack size by one and returns the element that was removed.</br>

isEmpty(): The isEmpty function checks if the stack is empty. It returns true if the stack has no elements, and false otherwise.</br>

isFull(): The isFull function checks if the stack is full. In case you are using an array-based implementation, this function ensures that the stack does not exceed its defined capacity.</br>

peak(): The peak function returns the value of the top element in the stack without removing it. It allows you to inspect the top element without modifying the stack.</br>

count(): The count function returns the number of elements currently in the stack. It provides the size or capacity of the stack at any given time.</br>

change(position, value): If you are using an array-based implementation, the change function allows you to modify the value of an element at a specified position in the stack.</br>
