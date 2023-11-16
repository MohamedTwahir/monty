# 0x19. C - Stacks, Queues - LIFO, FIFO
* What does LIFO and FIFO mean
LIFO = Last In First Out 
FIFO = First In First Out
# What is a stack, and when to use it
A stack is a linear data structure that follows Last In, First Out(LIFO) principle. Think of it like a stack of plates.
A stack supports two main operations:
1. Push: Adds an element to the top of the stack.
2. Pop: Removes the element from the top of the stack.
Stacks are used in various computer science applications, and here are some common scenarios when you might use a stack:
1. Function Calls and Recursion. each call is pushed onto call stack and when function is complete it is popped off the stack.
2. Undo Mechanisms in Applications. The undo operation simply pops the last action from the stack.
3. Expression Evaluation: They are often used to evaluate expressions, especially in programming languages.
4. Backtracking Algorithms: 
5. Browser History
6. Parsing compilers
# What is a queue, and when to use it
A queue is a fundamental data structure that follows the First In, First Out (FIFO) principle. In a queue, the first element added is the first one to be removed. Think of it like a queue of people waiting in line: the person who arrives first is the first to be served.
A queue supports two main operations:
* Enqueue (or Push): Adds an element to the back (end) of the queue.
* Dequeue (or Pop): Removes the element from the front (beginning) of the queue.
Queues are used in various computer science applications, and here are some common scenarios when you might use a queue:
* Task Scheduling:

In operating systems, queues are used to manage tasks and processes. The process that arrives first is the first to be executed.
* Breadth-First Search (BFS) in Graphs:
Queues are used in graph algorithms like BFS to explore nodes level by level.
* Print Queue:

In a print spooler, documents are printed in the order they are sent to the printer, forming a queue.

* Buffer in Networking:

In networking, queues are used to manage data packets. The first packet that arrives is the first to be sent.
* Order Processing:

In e-commerce systems, a queue might be used to process customer orders in the order they were received.
* Task Management in Multitasking Systems:

Queues are used in multitasking systems to manage tasks. The task at the front is the one currently being executed.
* Browsing History:

In web browsers, a queue can be used to manage the browsing history. The URL visited first is the first to be removed when the history limit is reached.
