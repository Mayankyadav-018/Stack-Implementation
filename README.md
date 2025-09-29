# EXPERIMENT NO – 19

* Aim: To study and implement Stack in C++ for managing data in Last-In-First-Out (LIFO) order.

* Tools Used: IDE, C++ compiler, arrays or linked lists, push and pop operations.

* Theory:

In C++, a Stack is a linear data structure that follows the LIFO (Last-In-First-Out) principle. The element inserted last is the one removed first, similar to a stack of plates.

-Top – Points to the last element added in the stack.

-Push – Operation to insert an element at the top of the stack.

-Pop – Operation to remove the element from the top of the stack.

-Peek/Top – Operation to view the element at the top without removing it.

-Stacks can be implemented using arrays, linked lists, or the STL stack library.

🔹 *Key Features of Stack:*

* Works on LIFO principle.

* Supports insertion and deletion from the top only.

* Can be implemented as:

* Simple Stack

* Dynamic Stack (using linked list)

* Stack using STL

🔹 *Advantages of Stack:*

-Provides an organized way to manage data with controlled access.

-Useful in function call management, recursion, expression evaluation, and backtracking.

-Forms the basis for advanced applications like Undo mechanisms, syntax parsing, and memory management.


# Implement the Stack Operations: Push and Pop:

This program demonstrates how to implement a stack data structure using an array. It supports standard stack operations like push, pop, and display. Overflow and underflow conditions are handled gracefully.

ALGORITHM:

1> Start

2> Define Stack class with:

* Private members: arr[MAX] and top

* Public methods:

push(value) : Add element to top of stack, check for overflow

pop() : Remove element from top, check for underflow

display() : Display all elements from top to bottom

3> In main function

* Create Stack object s

* Push elements 10, 20, 30

* Display stack

* Pop element and display stack after each pop

* Attempt pop on empty stack to check underflow

4> End



# Conclusion:

Stack implementation in C++ demonstrates how data can be managed in LIFO order. It allows efficient handling of operations where the most recent element needs to be accessed first. While simple stacks may have limitations like overflow and underflow, dynamic and STL-based implementations provide flexible and efficient solutions for real-world applications.
