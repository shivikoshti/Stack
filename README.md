# Stack
## Theory:
A stack is a fundamental data structure in computer science that follows the Last-In-First-Out (LIFO) principle. It is similar to a stack of books where the last book added is the first one to be removed. In C++, you can implement a stack using arrays or linked lists.
<img width="424" alt="Screenshot 2023-10-22 at 5 04 02 PM" src="https://github.com/Rutuja-117/Stack/assets/139907839/5920ad79-f6aa-49cb-af7c-432f6a48a128">
<img width="424" alt="Screenshot 2023-10-22 at 5 04 02 PM" src="https://github.com/Rutuja-117/Stack/assets/139907839/400fe27b-1e53-44d9-a028-34d1f2ba6b21">
### Functions:
push(element): The push function is used to add an element to the top of the stack. It increases the stack size by one and places the new element at the top.</br>

pop(): The pop function is used to remove the top element from the stack. It decreases the stack size by one and returns the element that was removed.</br>

isEmpty(): The isEmpty function checks if the stack is empty. It returns true if the stack has no elements, and false otherwise.</br>

isFull(): The isFull function checks if the stack is full. In case you are using an array-based implementation, this function ensures that the stack does not exceed its defined capacity.</br>

peak(): The peak function returns the value of the top element in the stack without removing it. It allows you to inspect the top element without modifying the stack.</br>

count(): The count function returns the number of elements currently in the stack. It provides the size or capacity of the stack at any given time.</br>

change(position, value): If you are using an array-based implementation, the change function allows you to modify the value of an element at a specified position in the stack.</br>
